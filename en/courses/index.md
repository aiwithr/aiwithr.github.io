---
layout: article
title: "Artificial Intelligence Series 1: Basic Machine Learning"
date: 2020-06-02T09:44:20-04:00
modified: 2020-06-27T14:56:44-04:00
excerpt: "Learn basic machine learning in Bangla: a hands-on course with Project Titanic — 4-week curriculum covering data visualization, decision trees and prediction, in R and Python."
lang: en
locale: en_US
alternate_bn: /courses/
image:
  feature:
  teaser:
  thumb:
share: false
ads: false
---
The 'Basic Machine Learning' training program

> Recipes tell you nothing. Learning techniques is the key.
>
> — Tom Colicchio

{% include toc.html %}

Honor code (drag to the right to view)
{: .notice-info}

```bash
1. In machine learning there is no *the solution*. Everyone is right.
2. We will try to learn; in this learning nothing is called wrong.
3. Everyone's *input* is valuable — give input at every stage.
4. Our effort will be to increase the model's *accuracy*.
```

## Why learn artificial intelligence?

1. Artificial intelligence is a technology that, largely without our knowing, has begun to surround us all. In one sentence: technology is being taught to make decisions just like humans do — for human needs. In healthcare, so patients get proper treatment and human error is reduced; and instead of testing a specific treatment on patients, this AI is used in simulations for 'drug discovery'. Today the technology's support behind COVID-19 drug discovery is no secret — without it the process would have taken far longer. Many countries are using this technology to control the pandemic.

2. Governments of developed countries use artificial intelligence for urban planning, mass transit systems, changing river courses, early flood detection, proper distribution and use of government resources, how much money pensioners may need in coming years (for example), crime prediction, city-wide traffic management — thousands of uses like these. Beyond its use in war gaming, the military's use of this technology entered the United States in 2014 as the 'Third Offset Strategy'. In 2018 the Pentagon presented a plan to spend 2 billion dollars on artificial intelligence.

3. The thing is this: perhaps we cannot quite grasp how it is happening — but everything around us is changing under the influence of this 'artificial intelligence'. Whether we want it or not, the thing has slipped inside everything — quietly. As we have seen, from healthcare to government work, transportation, education — whatever people want to do, this thing makes it easier. It is true that a very large power is coming into human hands — and very few people understand that. Where AI begins, the machine has to be taught — that is exactly where machine learning is needed. In other words: machine learning is the process by which machines are given intelligence, the very part of artificial intelligence that does that work.

4. A great 'AI for social good' movement is underway on earth, putting data to work for people. We have plenty of data in hand, but at this moment we cannot draw wisdom from it. This training will show the processes for extracting insight from data. It pays to know about machine learning, because its use has arrived in every sector. Artificial intelligence is a present — and future — skill set.

## How will we learn? Solving a real problem

Learning becomes very easy once you know the philosophy behind machine learning. You will then know where you are starting from, where you have to go — and where you stand right now. Since my machine learning friends are spread across the world, they all say one thing: if you want to learn machine learning, start with ['Project Titanic'](http://kaggle.com/c/titanic). *This is the gateway to machine learning.* Period. If you understand the problem properly, the solution is within reach.

## Learning outcome: the Titanic challenge

The year 1912. A true story. Thanks are due to James Cameron — he brought me back from the dead to tell the tale anew. The 'unsinkable' — meaning 'will not sink' — RMS Titanic goes down while crossing the Atlantic, on its very first voyage. It strikes an iceberg at 11:40 at night. Imagine: of 2,224 passengers and crew, almost everyone had gone to sleep in their cabins or at the bunks. What happened next is known to all.

1,502 people died on that voyage.

Around this true event this timeless problem has been built. Here we are given two datasets. In one, 12 fields about 891 people — including one field saying whether they survived that voyage or died. Notice the point: a real dataset. Everyone's names are on the internet. Their fates are given. There is nothing to invent here.

Now come to the problem. Another dataset has been given, with new people — outside those 891. We will find the fate of 418 passengers. 418 rows. There, every field is present except the one that says whether they lived or died. We do not know what became of them.

## Problem: predict who survived?

So, what is the Titanic challenge?
{: .notice}

From the dataset of those 418 people we must predict who survived and who died. When I first started working on this I was genuinely surprised. How is this possible? How will I know? Predicting people's deaths is not our job — and how could machine learning manage it?

<div class="badges">
	<span class="badge">R programming</span>
	<span class="badge info">Machine learning</span>
	<span class="badge warning">Kaggle competition</span>
	<span class="badge danger">Project Titanic</span>
	<span class="badge success">Prediction</span>
</div>

## At a glance (training program), links inside the table

Instructor-led class 2 hours + 1 hour working on the project = 3 hours in 1 day.

## Week 1 (Machine learning, Project Titanic)

| Day | Topic | What did I learn? |
| :--- | :--- | :--- |
| 1 | [What is machine learning?](https://rakibul-hassan.gitbook.io/mlbook-titanic/introduction/what-is-ml) | [The difference between conventional programming and machine learning](https://rakibul-hassan.gitbook.io/mlbook-titanic/introduction/why-data) |
| 2 | [Kaggle competitions](https://rakibul-hassan.gitbook.io/mlbook-titanic/kaggle/why-kaggle) | [Kaggle kernels and online hosted scripts](https://rakibul-hassan.gitbook.io/mlbook-titanic/kaggle/why-kaggle) |
| 3 | [Project Titanic](https://rakibul-hassan.gitbook.io/mlbook-titanic/project-titanic/titanic-story) | [The 'training' and 'test' datasets](https://rakibul-hassan.gitbook.io/mlbook-titanic/project-titanic/trg-test) |

## Week 2 (The "R" programming environment)

| Day | Topic | What did I learn? |
| :--- | :--- | :--- |
| 1 | ["R" programming environment](https://rakibul-hassan.gitbook.io/mlbook-titanic/r-environment/r-r-studio) | [Using "R" + "RStudio"](https://rakibul-hassan.gitbook.io/mlbook-titanic/r-environment/r-studio-installation) |
| 2 | [The project's GitHub scripts](https://rakibul-hassan.gitbook.io/mlbook-titanic/r-environment/github-script) | [Project Titanic + RStudio](https://rakibul-hassan.gitbook.io/mlbook-titanic/r-environment/r-commands) |
| 3 | [Project Titanic + RStudio, web version](https://rakibul-hassan.gitbook.io/mlbook-titanic/r-environment/r-commands) | [The Titanic dataset — Kaggle site](https://rakibul-hassan.gitbook.io/mlbook-titanic/r-environment/r-commands) |

## Week 3 (Prediction, data visualization)

| Day | Topic | What did I learn? |
| :--- | :--- | :--- |
| 1 | [First prediction: did everyone die?](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/1stprediction) | [Exploratory data analysis, Kaggle submission](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/1stprediction) |
| 2 | [Data visualization, about pictures](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/data-munging) | [What information did I get from data visualization?](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/data-munging) |
| 3 | [Second prediction: women or men?](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/2ndprediction) | [Women and children first](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/2ndprediction) |

## Week 4 (Decision trees, feature engineering)

| Day | Topic | What did I learn? |
| :--- | :--- | :--- |
| 1 | [The relationship between death and ticket price](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/3rdprediction) | [Third prediction, the "aggregate" command](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/3rdprediction) |
| 2 | [Decision trees, the fourth prediction](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/decision-tree) | [rpart, the predictive element](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/4thprediction) |
| 3 | [Data pre-processing, feature engineering](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/5thprediction) | [Data cleaning — putting the data right](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/6th-prediction) |
| 4 | [Seventh prediction (random forest)](https://rakibul-hassan.gitbook.io/mlbook-titanic/prediction/7th-prediction) | [Machine learning and our future](https://rakibul-hassan.gitbook.io/mlbook-titanic/whats-in-future/in-future)  |

## Online access, GitHub and RStudio Cloud

1. A [GitHub](https://github.com/) account is required.

2. Open an [RStudio Cloud](https://rstudio.cloud/) account before the class.

## Supporting book/documentation (online)

<figure>
	<a href="../images/mlbook1.jpg"><img src="../images/mlbook1.jpg"></a>
	<figcaption>Any one of the books used</figcaption>
</figure>

All links for Hatekolome Machine Learning (first or second edition)
{: .notice-info}

| Medium | Link |
| :--- | :--- |
|  [Online link](https://rakibul-hassan.gitbook.io/mlbook-titanic/) | [Gitbook — the complete book online](https://rakibul-hassan.gitbook.io/mlbook-titanic/) |
|  [Print book, Rokomari](https://rokomari.com/book/174186/) | [Rokomari.com](https://rokomari.com/book/174186/) |
|  [Print book, Adarsha](https://adarsha.com.bd/shop/hatekolome-machine-learning/) | [Adarsha Prokashoni](https://adarsha.com.bd/shop/hatekolome-machine-learning/) |
| [ Print book, Neelkhet](https://www.facebook.com/%E0%A6%B9%E0%A6%95-%E0%A6%B2%E0%A6%BE%E0%A6%87%E0%A6%AC%E0%A7%8D%E0%A6%B0%E0%A7%87%E0%A6%B0%E0%A7%80-%E0%A6%A8%E0%A7%80%E0%A6%B2%E0%A6%95%E0%A7%8D%E0%A6%B7%E0%A7%87%E0%A6%A4%E0%A6%A2%E0%A6%BE%E0%A6%95%E0%A6%BE-996072720590097/) | [Hak, Manik Library and many more, 01735742908, 01820157181](https://www.facebook.com/ManikLibraryOnline) |
|  [E-book, Amazon](https://www.amazon.com/dp/B089NTNG3R/) | [Kindle edition](https://www.amazon.com/dp/B089NTNG3R/) |
|  [E-book, Google Books](https://play.google.com/store/books/details?id=7xbpDwAAQBAJ) | [Google Play Books in Bangladesh](https://play.google.com/store/books/details?id=7xbpDwAAQBAJ) |

## Mobile-friendly links (books)

1. [Online link — the complete book online](https://rakibul-hassan.gitbook.io/mlbook-titanic/)

2. [Print book, Rokomari](https://rokomari.com/book/174186/)

3. [Print book, Adarsha](https://adarsha.com.bd/shop/hatekolome-machine-learning/)

4. [Print book, Neelkhet]()

5. [E-book, Amazon](https://www.amazon.com/dp/B089NTNG3R/)

6. [E-book, Google Books](https://play.google.com/store/books/details?id=7xbpDwAAQBAJ)

## Table of contents of the supporting book/documentation
<figure>
	<a href="../images/toc1.png"><img src="../images/toc1.png"></a>
	<figcaption>Book table of contents 1</figcaption>
</figure>
<figure>
	<a href="../images/toc2.png"><img src="../images/toc2.png"></a>
	<figcaption>Book table of contents 2</figcaption>
</figure>
<figure>
  <a href="../images/toc3.png"><img src="../images/toc3.png"></a>
	<figcaption>Book table of contents 3</figcaption>
</figure>
## Supporting videos (if you miss a class)

YouTube playlist: [Machine Learning (2nd edition) book video series](https://www.youtube.com/playlist?list=PL5NPSn95n_L4AUOUjfZamspLzCAEeJW3p)

Daily input about the training can be given at 01713095767. Thank you.
{: .notice}

## Application rules

Correctly answering the subject described in Hatekolome "Data Analytics" (number 5) is required

- [x] 1. Free of charge (the price of knowledge depends on the person), first 5 batches. My job here is to walk you along the path of data; putting you on that path is my responsibility. All you need is "interest". It starts "no coding". Only students from a non-programming background should apply.

- [x] 2. The reason for offering this free is entirely personal. Batches of 25 will be formed through 1-1 interviews with students based on the information you provide.

- [x] 3. Experience says that because data is used little in this country, we cannot attract this 'extraordinary' skill set. Alongside your current job, this skill will help you in future "job openings". Jobs are coming. You need one skill. Curiosity (a noun), interest, eagerness, an inquisitive mind. Nothing else will be needed. The rest I will teach you.

[Batch 1: 17 July – 14 August 2021, 90-minute online classes (Google Meet). Friday–Saturday, mornings or evenings. Discussion-based. 10 female students + 10 male students + 5 (my picks)]
{: .notice-info}

- [x] 4. I have seen that in cognitive reasoning, meta-analysis and pattern analysis from data, female students are not behind — hence an equal number of vacancies.

- [x] 5. Since this free "mentorship" service has no price, it requires a great 'commitment' from you, to yourselves. To test your strong 'commitment', therefore, these three questions. Help me by answering them properly — so that I can help you properly. I expect brilliant answers. 'Selection' will be based on the answers.

- [x] 6. For your convenience, the answers to these three questions are on a YouTube playlist. You can watch by skipping the first few. [Playlist:](https://youtube.com/playlist?list=PL5NPSn95n_L4Z5bpCOqHW_QU8nxgywGM2)

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Course",
  "name": "Artificial Intelligence Series 1: Basic Machine Learning",
  "description": "Basic machine learning training in Bangla — hands-on learning with Project Titanic, a 4-week curriculum: data visualization, decision trees and prediction.",
  "url": "https://aiwithr.github.io/en/courses/",
  "inLanguage": "bn",
  "provider": {
    "@type": "Person",
    "name": "Rakibul Hassan",
    "sameAs": ["https://aiwithr.github.io/", "https://www.youtube.com/@aiwithr"]
  },
  "hasCourseInstance": {
    "@type": "CourseInstance",
    "courseMode": "Online"
  }
}
</script>

(The deadline for this application was 08 July 2021; you could edit your answers within that period)
{: .notice}
