# aiwithr.github.io — SEO Reorganization Record

Last updated: 2026-10-13
Scope: https://aiwithr.github.io (repo aiwithr/aiwithr.github.io, branch master)
Purpose: historical record of what was changed for SEO and what content was updated.

---

## 1. Technical SEO fixes

- `<html lang="bn">` set on all pages (`_includes/default.html`, `_includes/home.html`).
- Meta description fallback added (site.description) where page excerpt was missing (`default.html`, `home.html`).
- Favicon + apple-touch-icon links added to `<head>` (site favicon was missing — Seobility critical).
- Single-H1 fix: homepage renders exactly one `<h1>` (page-title guard in `home.html`); H1 keyphrase also present in visible body text.
- Open Graph (`_includes/open-graph.html`):
  - `og:description` fallback added.
  - `og:image` added with feature-image → site-logo fallback (all pages share a valid image).
- Analytics: GA4 measurement ID `G-N9JZXN7KF9` added in `_includes/header.html`, replaced dead Universal Analytics `UA-5574703-3`.
- Structured data: **Person JSON-LD** in `open-graph.html` — name Rakibul Hassan, `image`, 9 `sameAs` (LinkedIn, GitHub, Twitter, Facebook, WordPress, YouTube, TEDx, etc.), `worksFor` Link3 Technologies Limited, `jobTitle` "Director AI Business and Transformation", `knowsAbout`, `subjectOf` (Roar Media profile), description citing 11+ books and 600+ videos.
- `_config.yml`: `owner.name` → "রকিবুল হাসান (Rakibul Hassan)", `owner.bio` synced to current role/book count.
- `robots.txt` verified live (HTTP 200, contains `Sitemap:` directive); `sitemap.xml` verified live (HTTP 200).

## 2. Site hygiene (removals)

Deleted junk/duplicate files so they no longer appear in the sitemap:

- `classes/index - Copy.md`
- `classes/index_2.md`
- `_posts/delete/privacy.md`
- `_posts/delete/2014-02-03-sample-media-page.md`

Result: `sitemap.xml` = **34 clean URLs** (all real pages).

## 3. Content updates

### Homepage (`index.md`)
- New intro paragraph added below the tile grid, with `.notice` styling:
  "এই সাইটটা - ইন্টেলিজেন্ট সিস্টেমের সন্ধানে: (১) কৃত্রিম বুদ্ধিমত্তা (২) মেশিন লার্নিং বই (৩) হাতে-কলমে টিউটোরিয়াল এবং ওয়ার্কশপের সমন্বয়।"

### About (`about/index.md`)
- Full Bangla identity block refreshed: 11+ books (publishers আদর্শ, তাম্রলিপি — Rokomari bestseller), TEDxRUET speaker, former Director BTRC / Project Director ILIS, current **Director AI Business and Transformation, Link3 Technologies** (updated from CTO).
- Bullets (7), each with links:
  - **বই:** 'হাতেকলমে মেশিন লার্নিং' সিরিজসহ → Rokomari author page `rokomari.com/book/author/61248/rakibul-hassan`, plus **বাংলায় কৃত্রিম বুদ্ধিমত্তা প্যাকেজ** → `boipokabd.com/books/bangla-kritrimo-buddhimotta-pjakejo`.
  - **ভিডিও কন্টেন্ট:** YouTube `@aiwithr` — "Building Intelligent Systems with Rakib", 600+ videos; plus secondary handle `youtube.com/@RaqueebHassan`.
  - **ওয়ার্কশপ:** Kamla workshop (raqueeb.github.io/kamla_wksp).
  - **টেডএক্স:** TEDxRUET speaker page.
  - **সংবাদ ও ফিচার:** Roar Media profile (2020).
  - **সোশ্যাল ও প্রফেশনাল:** LinkedIn, GitHub, Twitter/X, Facebook, WordPress, The Thinking School.
  - **প্রিন্ট মিডিয়া:** /print/ (52 links).
- Author photo added: `images/rakibul-hassan.jpg` (1086×1448) + `images/bio-photo.jpg` (160×160 byline thumb).
- English block + front-matter excerpt synced (role, 11+ titles, 600+ videos).

### Resources (`resources/index.md`)
- New `## প্রিন্ট মিডিয়া` section (link to /print/) inserted **before** the YouTube section; appears in page TOC.

### Footer (`_data/footer.yml`)
- New link: **প্রিন্ট মিডিয়া** → `/print/` (site-wide).
- Spelling fix: প্রাইভেসী → **প্রাইভেসি**.

## 4. Homepage layout fixes (UX affecting SEO engagement)

- `.notice` mixin: added `clear: both` (`_sass/_notices.scss`) — notice box no longer paints over the floated tile grid (desktop bug where homepage looked like one black box; tiles were hidden).
- `.home-page` body class (`_layouts/home.html`) + `_sass/_layout.scss`: zeroed footer `margin-top` and notice `margin-bottom` on homepage → no white gap after the black box.

## 5. Verification (all passed live)

- `lang=bn`, meta description, single H1, favicon, GA4 ID present in homepage HTML.
- Person JSON-LD parses; Person fields correct.
- `sitemap.xml` 34 URLs, no junk; `robots.txt` 200 + Sitemap directive.
- About: 11+/600+ text, photo, both new book links, both YouTube handles live.
- Footer: print link live, privacy spelling corrected.
- Resources: print link appears before YouTube link in source order.
- OG image fallback works on pages without feature images.

## 6. SEO tooling status & outstanding manual steps

- Seobility pre-fix On-page score: 52%. Criticals fixed: language, meta description, multiple/empty H1, favicon.
- Known limitation (accepted): www/non-www canonical split — GitHub Pages cannot host both apex/redirect variants.
- **Owner to-do:**
  1. Google Search Console — resubmit `https://aiwithr.github.io/sitemap.xml`; spot-check key URLs (URL Inspection → Request indexing).
  2. Seobility — request re-crawl for updated score.
  3. GA4 — confirm hits arriving on `G-N9JZXN7KF9`.
  4. (Optional) Bing Webmaster Tools for extra coverage.

## 7. Commit log

| Commit | Summary |
|---|---|
| `f3f41e2` | SEO overhaul: lang/meta-description/favicon fixes, single H1, GA4, Person JSON-LD, author identity block |
| `63d5b41` | Homepage intro moved below tiles with notice styling |
| `238db8c` | About page content refresh; sync role and book count in structured data |
| `75bcfc6` | Fix notice box overlapping homepage tiles; remove extra footer gap on home |
| `74debbe` | Add print media link before YouTube section on resources |
| `71828d0` | Add print media link to footer; fix privacy spelling |
| `20dcda6` | About: link books to Rokomari author page; add secondary YouTube handle |
| `dcb7764` | About: add Boipoka Bangla AI package link in books bullet |
