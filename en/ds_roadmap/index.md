---
layout: article
title: "Data Science / Analytics Roadmap"
date: 2021-12-17T13:57:25-04:00
modified: 2022-01-16T22:08:14-05:00
alternate_bn: /ds_roadmap/
lang: en
locale: en_US
excerpt: "Data Science and Analytics Roadmap — a step-by-step guide from absolute zero: essential skills, tools, courses, and career pathways for beginners."
tags: [data science, data analytics]
image:
  feature:
  teaser:
  thumb:
share: true
---

{% include toc.html %}

![All books by Rakibul Hassan]({{ site.url }}/images/aibook2.jpg)
<div class="badges">
	<span class="badge">Data Science</span>
	<span class="badge info">Data Literacy</span>
	<span class="badge warning">Business Analyst</span>
	<span class="badge danger">Data Analyst</span>
	<span class="badge success">Machine Learning Engineer</span>
</div>

A data science roadmap from absolute zero — for absolute beginners! You do not need a PhD to do data science!
{: .notice-info}

> Recipes tell you nothing. Learning techniques is the key.
>
> — Tom Colicchio

There is extensive discussion across the industry about how to become a proficient data scientist or data analyst, and how long that journey truly takes. The answer is largely relative: it depends entirely on how one perceives data and how deeply one intends to work with it. If you want to work with data, starting with Data Analytics (extracting actionable knowledge from data) is the ideal entry point. Transitioning from Data Analytics (typically 5–6 months of focused learning) to comprehensive Data Science (10–16 months) is entirely achievable.

Data Science is an enormous banyan tree of a discipline. In my view, before diving headlong into a subject as vast as Data Science, understanding how to extract actionable insight from data through Data Analytics makes the subsequent transition to Data Science far smoother. Once you grasp how data is handled and what tangible outcomes it can produce, the underlying science becomes remarkably intuitive. Many learners browse thousands of disjointed data science tutorials online, only to lose momentum halfway because their foundational concepts were never properly anchored. That is the exact reason for formulating this roadmap.

Let me reiterate:

Here, we present a straightforward, selective Data Analytics Roadmap, incorporating specifically the asterisk-marked (*) components from the overarching Data Science roadmap. Again, Data Science is vast; mastering Data Analytics first is the easiest and most practical path forward.
{: .notice-info}

| Timeframe | Track |
| :--- | :--- |
| 5–6 Months | Data Analytics |
| 10–16 Months | Data Science |

Before embarking on any learning journey, having a structured learning framework is invaluable. This roadmap is designed to clarify what core skills to incorporate, what high-quality learning resources are currently available, and which industry-standard tools are actively in use. A learning framework is fundamentally a process; once you thoroughly understand the process, you will understand which tools to adopt — and those tools will naturally evolve over time.

For this reason, I advise against becoming rigidly "tool-dependent." My philosophy is straightforward: once you master the underlying process, picking up any specific tool becomes easy. You need a clear broad-line understanding of what you are learning, why you are learning it, and how it directly relates to real-world outcomes.
{: .notice}

## Learning Roadmap: What Is It?

Think of it as a conceptual mind map, where cultivating multi-level skills is neither daunting nor chaotic. Here, we outline the exact skills you will want to acquire, how to measure the tangible outcomes of each learning stage, and how to utilize the relevant tools effectively. Alongside this, we examine the practical techniques that accelerate mastery, pointing out where concepts become straightforward and where complexity begins to increase in subsequent stages.

## Data Science Summary, (*) = Data Analytics

| Data Science Domain | Analytics Track |
| :--- | :--- |
| End-to-End Pipeline | Optional |
| Hierarchy of Needs | * |
| Data Science Workspace | |
| Basic Mathematics, Linear Algebra | |
| Statistics, Distributions | * |
| Programming Skills: Python / 'R' | * |
| Exploratory Data Analysis (EDA) | * |
| Data Visualization | * |
| Professional Visualization Tools | * |
| Business Analytics / Intelligence Tools | * |
| Model Building, Machine Learning | |
| SQL Skills | * |
| NoSQL (Optional) | |
| Data Analytics Capstone Project | * |
| Data Science Capstone Project | |
| Data Engineering, APIs | |

How does one become a successful data scientist or analyst? At the very outset, completing a concise, small-scale end-to-end project (even with just a few lines of data) provides immense clarity, making everything downstream far simpler. Grasping the data pipeline is essential: unless you understand how data flows through a pipeline and undergoes transformation through sequential operations, mastering this discipline remains elusive. That is why two focused projects are recommended.

<figure>
	<a href="{{ site.url }}/images/pipeline.png"><img src="{{ site.url }}/images/pipeline.png" alt="Data Pipeline Step by Step Diagram"></a>
	<figcaption>The Data Pipeline, Step by Step</figcaption>
</figure>

Next, acquiring a foundational grasp of mathematics and statistics makes forward progress significantly easier. I am not suggesting that you must master hardcore theoretical mathematics or statistics; rather, you need the operational intuition required to execute data projects effectively. Later, in the machine learning phase, having this foundation will make it clear how statistical algorithms and mathematical transformations operate under the hood.

Alongside theoretical understanding, developing familiarity with a programming environment is vital in this segment. For individuals with no prior coding background, the 'R' programming environment is virtually a godsend. Those with existing programming exposure can jump straight into Python. However, for developing a deep, intuitive understanding of data analysis, 'R' still provides an unmatched learning curve.

Ultimately, decisions must be driven by knowledge extracted from data. From that perspective, mastering data visualization is critical. Both the 'R' and Python ecosystems feature world-class visualization libraries that were developed specifically for this purpose. Finally, after absorbing these concepts, you must test your skills directly in real-world scenarios. To verify whether you can apply what you have learned to actual life challenges, completing several capstone projects is essential. That concludes the overview — let us dive into the detailed guidelines.

## Basic End-to-End Pipeline Concept (Optional)

To grasp the overarching big picture of data science, Monica Rogati's "Data Science Hierarchy of Needs" is an essential conceptual model. Understanding this model embeds the entire roadmap firmly in your mind. Examine the diagram below. You should also search for variants of this diagram online to broaden your perspective. The diagrams are kept in English for technical clarity, but everyone should explore the analogy with Maslow's classic hierarchy of needs.

<figure>
	<a href="{{ site.url }}/images/need1.png"><img src="{{ site.url }}/images/need1.png" alt="Monica Rogati Data Science Hierarchy of Needs Diagram"></a>
	<figcaption>Monica Rogati's Classic Hierarchy of Needs</figcaption>
</figure>

## Data Science Hierarchy of Needs *

Examine the interconnected diagrams below. Every layer connects directly to the one above it.

<figure>
	<a href="{{ site.url }}/images/ds_needs.jpg"><img src="{{ site.url }}/images/ds_needs.jpg" alt="Data Science Hierarchy Operational Breakdown"></a>
	<figcaption>Detailed View of the Data Science Hierarchy</figcaption>
</figure>

From an operational standpoint, the diagram above illustrates how every level interconnects, offering a clear perspective on where you want to position your career. Paralleling Maslow's theory, the base of the data science hierarchy begins with data collection mechanisms. At the end of the day, data is the raw fuel of data science: without proper instrumentation, server logging, relational databases, sensor streams, and external data feeds, ascending to higher tiers is impossible. The specific tools required for this foundation will be detailed further below.

Once data is reliably collected, the fifth tier centers on storage and infrastructure. Establishing reliable data flows, ETL (Extract, Transform, Load) pipelines, and stable infrastructure paves the way for the fourth tier. In this fourth stage, exploratory data analysis and transformation occur — encompassing data cleaning, outlier detection, and anomaly resolution. Once data is properly cleaned and structured, it can be passed upward to the third tier.

This third tier is pivotal: here, data aggregation and labeling take place. Extracting actionable business knowledge through analytics (the primary focus of this guide), establishing core KPIs and operational metrics, and performing feature segmentation all reside here. This makes the third stage highly appealing to many practitioners. However, working upward from the foundational collection tier reveals the true effort involved: data collection and data cleaning are universally acknowledged as the most demanding phases, typically consuming roughly 80% of a data team's time.

When reliable insights are established at the third tier, the second tier enables baseline machine learning algorithms and empirical experimentation, such as A/B testing frameworks. In reality, the vast majority of commercial products and enterprise solutions are built right here at the second tier. Advanced deep learning architectures and artificial general intelligence sit at the apex — a domain that beginners need not stress over initially. Crucially, open-source frameworks power every single layer of this hierarchy worldwide: every capability you need exists within the global open-source ecosystem.

## Deep Dive: Hierarchy of Data Science Needs (Advanced Context)

**This distinction is vital for those pursuing a long-term data science career. We review these fundamentals so students can navigate the field with clarity.**

Before getting caught up in industry hype, understanding the distinct boundaries between a Data Analyst, a Data Engineer, and a Data Scientist clarifies your career trajectory. Many aspiring professionals struggle to determine which role aligns with their strengths. To complicate matters, corporate job postings often conflate these titles, creating widespread confusion. The most effective way through this ambiguity is to scrutinize the job responsibilities and technical descriptions rather than the job title alone. The detailed responsibilities reveal exactly what the organization requires you to execute, making the headline label largely secondary.

To unpack this clearly, we revisit Monica Rogati's hierarchy from an operational perspective. Before considering advanced roles, one must understand how, where, and when data is operationalized. If data collection mechanisms are flawed, any machine learning or artificial intelligence initiatives built on top will fail to yield meaningful results. Artificial intelligence will not magically resolve systemic operational shortcomings, nor is advanced machine learning required for every enterprise problem. Abundant "low-hanging fruit" exists in everyday business that can be resolved with straightforward analytics. However, to leverage data in business, you must first know how it is collected, validated, and stored. Until disparate data streams are systematically organized, reliable data manipulation remains out of reach.

Whether corporate data resides in relational databases or standard CSV spreadsheets, robust data pipelines are essential to transport and transform data reliably across schemas. While pipelines may seem abstract initially, they are indispensable for solving complex enterprise challenges at scale. Managing these distributed storage infrastructures, moving data across systems, and ensuring format consistency is the core mandate of Data Engineers.

To architect these pipelines, Data Engineers must possess solid mastery of data structures. Their primary responsibility is cleaning, transforming, and optimizing data so that downstream users can query it efficiently. Unqueried data delivers zero value. For instance, during data preparation, engineers must implement deduplication strategies to eliminate redundant records. Proficient SQL querying at this layer dramatically reduces friction, providing baseline operational views across the organization.

Next come Data Analysts, Business Analysts, Product Managers, and Software Engineers, who query this structured data to answer critical business questions. By executing targeted queries, they uncover root causes and extract actionable analytical insights. Formulating the right questions is the prerequisite to obtaining meaningful answers. Product roadmaps, marketing allocations, and executive decisions originate primarily from this stage. This is the natural habitat of the Data Analyst. Because earlier engineering stages transformed the raw data, analysts can focus entirely on querying and statistical exploration.

In the subsequent stage, data is structured with sufficient granularity to support experimentation frameworks, such as A/B testing. Here, teams fine-tune products to determine which variations perform best across customer segments — answering whether a blue or red CTA button drives higher engagement, identifying high-impact product features, and prioritizing incremental improvements.

At this level, simple predictive models like linear regression can be deployed to anticipate future user behavior and feature preferences. Straightforward baseline algorithms provide predictive visibility without unnecessary complexity.

At the very summit, implementing Deep Learning and Artificial Intelligence requires immaculately cleaned, well-labeled training data. That is why every underlying pipeline in the preceding tiers must function flawlessly. Accurately identifying prerequisites at lower tiers makes higher-level machine learning implementations straightforward. When conventional linear models fall short, advanced deep learning architectures can be explored.

## Job Descriptions: Where Do Analysts, Engineers, and Scientists Fit?

Where do these roles situate themselves within the pyramid? In practice, Data Engineers primarily operate across the bottom two tiers: collection, ingestion, storage, and transformation. Software Engineers often build data instrumentation within frontend and backend systems to capture user interactions. Data Analysts focus on the aggregation, analysis, and metric tiers: organizing data to enable informed business decisions and answering core operational questions.

A talented analyst identifies strategic company directions, uncovers emerging feature opportunities, and bridges technical analysis with business acumen. Exceptional communication skills are indispensable for analysts, enabling them to align diverse stakeholders around unified data-backed goals. While many corporate postings label analysts as data scientists, pure Data Scientists typically command deeper mathematical and algorithmic toolkits, formulating custom machine learning models to solve complex predictive problems.

In specialized settings, Data Scientists collaborate with Research Scientists and Machine Learning Engineers to tackle challenging algorithmic problems, often supported by PhD-level specialists. However, organizational structure varies: at early-stage startups, a single data professional often executes tasks across all tiers, while tech giants deploy specialized roles. The overarching takeaway is simple: whenever reviewing job openings, always focus on the detailed job responsibilities to evaluate whether the role aligns with your skillset.

<figure>
	<a href="{{ site.url }}/images/need2.png"><img src="{{ site.url }}/images/need2.png" alt="Operational Roles Mapped to the Hierarchy"></a>
	<figcaption>Operational Roles Mapped to the Hierarchy</figcaption>
</figure>

My first two books were crafted to guide you through this journey. *Hatekolome Machine Learning* blends practical fundamentals with real-world industry experiences and personal anecdotes. My second book, *Python Machine Learning from Zero*, is designed so that students from completely non-programming backgrounds can learn without barrier. Using hands-on exercises in Python and 'R' (requiring no prior coding experience), it demystifies data pipelines step by step.

Once you grasp the concept of pipelines, completing one or two concise, real-world projects establishes strong intuition. You do not even need to buy books initially. The two foundational projects are:

| Project | Book Link |
| :--- | :--- |
| Iris Species Classification Project | [Python Machine Learning from Zero](https://raqueeb.gitbook.io/scikit-learn/) |
| Project Titanic Survival Prediction | [Hatekolome Machine Learning](https://rakibul-hassan.gitbook.io/mlbook-titanic/) |

Because humans learn exceptionally well through visual demonstrations, the following walkthrough video offers valuable intuition. Replicating this hands-on will solidify your understanding:

<iframe width="560" height="315" src="//www.youtube.com/embed/GcM3W3gjVjc" frameborder="0"> </iframe>

## (Python) Data Science Workspace: Anaconda

Everything you need is included here. All the open-source tools spanning the Data Science Hierarchy of Needs are bundled within the Anaconda distribution, including Jupyter Notebooks. If you prefer not to install local software, Google Colaboratory provides a ready-to-use cloud environment.

## Basic Math, Linear Algebra, and Calculus

To explore the inner workings of data science, linear algebra is a fantastic starting point. Before manipulating data, understanding scalars, vectors, and matrices is vital for conceptualizing how data is held in memory. Gaining intuition into transformations, matrix inversion, transpositions, and matrix multiplication is essential. Calculating dot and cross products can be mastered easily via Khan Academy, as I did myself. Exploring linear dependency, orthogonality, and vector combinations is thoroughly explained across platforms like Khan Academy and Medium.

For calculus, calculating derivatives, formulating differential equations, and computing integrals will naturally enter the picture. In practice, these operations can be executed in just a few lines of Python or 'R'. However, understanding the underlying mathematical concepts helps you comprehend how algorithms generate their final outputs. Grasping math is particularly valuable for mastering the mechanics of data engineering.

## Statistics, Descriptive Analysis, and Distributions *

Statistics forms the core foundation underpinning data science. Once computerized data processing took center stage, statistical methodologies became embedded into machine learning. Understanding descriptive statistics and probability distributions makes data science infinitely clearer. Central tendency measures — mean, median, mode, minimum, maximum, and quantiles — tell the structural story of a dataset. Numerous intuitive lessons on the normal distribution are freely available online.

Furthermore, histograms, scatter plots, and box plots have become everyday diagnostic tools. Concepts like variance and standard deviation are readily accessible through Khan Academy. In research contexts, confidence intervals, hypothesis testing, population proportions, p-values, and significance tests are routine. While these concepts may seem intimidating initially, they are remarkably intuitive once visualized with real data.

Core probability concepts — experimental probability, independent and dependent events, and conditional probability — should also be understood. Google searches and Khan Academy remain your most dependable allies.

## Programming Skills: Python and 'R' Environments *

As emphasized earlier, applying data science or analytics effectively requires a programming environment. We focus on two globally recognized environments. Beginners often experience confusion regarding how programming fits into data science. First, understand *why* programming is used: at the start of any data problem, we must extract data from various sources using APIs (Application Programming Interfaces) or web scraping. Subsequently, we write code to perform data manipulation, cleaning, and ETL transformations. That is where programming enters — not before.

### The 'R' Programming Environment

For learners arriving from non-programming disciplines, the 'R' programming environment is a godsend. Specifically designed for statistical computing, 'R' accelerates the initial learning curve of data analytics. Operations that require five lines of code in Python can often be accomplished in a single concise line utilizing R's vast library ecosystem. Furthermore, R's data visualization toolkits remain world-class. My first book, *Hatekolome Machine Learning*, provides a gentle introduction that even high school students can follow with ease.

### The Python Programming Environment

Learners with prior programming experience typically start directly with Python. Like 'R', Python's extensive suite of specialized data science packages makes the learning trajectory smooth and accessible. My book *Python Machine Learning from Zero* covers foundational workflows, while *Hatekolome Python Deep Learning* guides readers through advanced implementations.

## Four Data Tasks Using Python

To understand data science with Python, we can categorize our work into four fundamental operations. The journey begins with data collection: if data cannot be reliably ingested into your computing environment, no meaningful analysis can proceed.

## (Python) Data Collection

For initial data collection, several foundational Python libraries are utilized, among which pandas is paramount. Truthfully, there is virtually nothing involving tabular data that pandas cannot handle. For advanced data acquisition, web scraping frameworks like Selenium and Scrapy can be deployed.

## Exploratory Data Analysis (EDA) *

The subsequent phase is data exploration. After collecting data, cleaning and transforming it requires specialized libraries. While similar tools are used across stages, new analytical paradigms emerge here. For numerical storage and array manipulation, we rely heavily on NumPy and pandas. This phase — Exploratory Data Analysis (EDA) — allows us to inspect data structures, identify anomalies, and uncover underlying patterns.

## Data Visualization (EDA and Exploration) *

Data visualization is essential for uncovering hidden structures within data. The human brain processes visual patterns with extraordinary speed: plotting data across coordinate axes exposes correlations and trends that raw numbers conceal. Bar charts, box plots, and scatter plots reveal how features interrelate. This visual intuition reinforces the reality that events in our world follow discernible patterns. In Python, Matplotlib and Seaborn are the premier libraries for executing this work.

## Business Analytics and Intelligence Tools *

> 94% of people using data in their current job role agree that data helps them do their job better.

To communicate analytical insights effectively to organizational stakeholders — whether senior management or client teams — identifying relationships through scatter plots and box plots requires professional business intelligence tooling. While Seaborn is outstanding for open-source exploration, enterprise platforms like Microsoft Excel, Google Sheets, Tableau, and Microsoft Power BI operate on a different plane of efficiency. They enable rapid dashboarding and executive reporting. I have created numerous tutorials demonstrating practical workflows in Excel, Tableau, and Power BI.

## Excel, Google Sheets, Tableau, and Power BI *

While Python provides immense open-source flexibility, enterprise organizations routinely deploy proprietary business intelligence platforms. These platforms are engineered to minimize the turnaround time required for decision-makers to generate sophisticated visual reports. Extensive research has gone into optimizing their user experience. The ubiquitous presence of Microsoft Excel on almost every enterprise workstation is proof of its enduring utility. Google Sheets offers free cloud flexibility with certain enterprise scaling boundaries, while Tableau and Power BI represent top-tier business intelligence platforms that command dedicated enterprise investments.

## (Python) Model Building and Machine Learning

The final phase of data science centers on translating analytical insights into predictive models. The knowledge derived from exploratory data analysis is operationalized into predictive algorithms through machine learning. Building, evaluating, and fine-tuning these models rests heavily upon statistical principles and linear algebra. The algorithmic tools handle computation, but conceptual understanding of why a model behaves as it does comes from mathematics and statistics.

At the baseline level, we utilize Python's scikit-learn library, transitioning to the TensorFlow framework for deep learning. For academic and cutting-edge research, PyTorch is an outstanding choice. scikit-learn is globally recognized as one of the best-documented, most accessible libraries in software engineering. My book *Python Machine Learning from Zero* covers these foundations, while *Hatekolome Python Deep Learning* explores advanced neural architectures.

## SQL Querying Skills *

Beyond collecting data, understanding where data resides and how relational databases operate is indispensable. Grasping relational database architecture and mastering SQL (Structured Query Language) to extract targeted datasets is a non-negotiable skill for both data analysts and data scientists.

Key SQL concepts to master include DDL statements (`CREATE`, `ALTER`, `DROP`, `TRUNCATE`, `RENAME`), DML statements (`SELECT`, `INSERT`, `UPDATE`, `DELETE`), DCL statements (`GRANT`, `REVOKE`), and TCL transactions (`COMMIT`, `ROLLBACK`). Furthermore, understanding table joins, unions, and aggregations is essential. Beginners can get started with the open-source MySQL relational database system.

## NoSQL (Optional)

Alongside relational databases, the popularity of NoSQL databases has surged to manage unstructured and semi-structured datasets. For non-tabular, flexible schema storage, NoSQL provides immense scalability. In this domain, exploring MongoDB offers valuable experience that will serve your engineering career well.

## Data Science / Analytics Capstone Projects

To achieve genuine mastery, executing a complete, real-world project from data ingestion to final reporting is mandatory — without it, theoretical learning quickly evaporates. Working on industry-aligned capstone projects connects foundational theory directly with enterprise problem-solving.
{: .notice-info}

## Global Superstore Project (Analytics) *

Here, we explore hands-on workflows centered on global superstore supply chain and sales management — an intellectually stimulating, highly realistic enterprise scenario.

### Movie Recommendation Project

The algorithmic recommendation engines powering Netflix and YouTube mirror the recommendation architectures deployed by Amazon, AliExpress, and Daraz to suggest products users are most likely to purchase. Developing a simplified collaborative filtering recommendation engine demystifies a massive pillar of modern e-commerce engineering.

### Customer Churn Management Project

Customers represent an organization's most valuable asset. Predicting which subscribers will remain active and which are likely to churn enables proactive customer retention. Similarly, forecasting employee turnover allows Human Resource leadership to address dissatisfaction early, preventing costly attrition.

## Portfolio Showcasing *

Beyond executing projects, showcasing your work publicly is crucial. Public portfolios generate constructive peer feedback and build professional confidence. Maintaining a dedicated portfolio website bridges the gap between what you have learned and what you can deliver to employers. For building an initial portfolio, GitHub Pages provides an extraordinary, free platform — this very website is hosted via GitHub Pages. Link your project writeups, notebooks, and professional networking profiles there.

## Optional: Data Engineering and APIs

Developing foundational literacy in data engineering, model deployment, and API communication — particularly JSON payloads, REST conventions, and OpenAPI standards — enables you to integrate your work seamlessly across any software ecosystem. Additionally, concepts from graph theory, network analysis, time series forecasting, operational optimization, and combinatorics frequently prove advantageous.

## Building the Data Science Community

We must build this community together.

### First 4 Bangla Books for Data Science / Analytics

![First 4 Bangla Books for Data Science and Analytics]({{ site.url }}/images/teqt.jpg)
<div class="badges">
	<span class="badge">R Programming</span>
	<span class="badge info">Python Programming</span>
	<span class="badge warning">Exploratory Data Analysis</span>
	<span class="badge success">Data Visualization</span>
	<span class="badge danger">Python Deep Learning</span>
</div>
