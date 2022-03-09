#### Editor's Note: `Take Two`

In the old days of 2013, the OSDSM was born. Then, there were "little to no Data Scientists with 5 years experience, because the job simply did not exist." _David Hardtke, Nov 2012_. Since then, history has witnessed a few things...

- Data Scientists working across industries and the world
- social media manipulated to disrupt elections
- BLM and #metoo
- machine learning begins falling to engineering
- a pandemic
- climate change disasters becoming very frequent
- remote work becomes normal

In that decade, Data Science has seen growth of jobs, shortfall of goals, success in many industries, abject failure in others, and nefarious use cases. In particular, the adverse consequences and complications of data-driven systems have become core to the Data Science conversation. Data-enabled technologies have enabled a litany of problematic applications -- the [ethical implications of learning from data](http://machinebias.org), [undermining elections with psychographics](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal), [dismal gender (Men=74%) and BIPOC diversity in the AI field](https://www.nytimes.com/2016/06/26/opinion/sunday/artificial-intelligences-white-guy-problem.html), a revived [eugenics](https://www.technologyreview.com/s/612275/sociogenomics-is-opening-a-new-door-to-eugenics/), an [explainability crisis](https://hbr.org/2018/07/when-is-it-important-for-an-algorithm-to-explain-itself), [facial recognition](https://www.theguardian.com/technology/2014/may/04/facial-recognition-technology-identity-tesco-ethical-issues) used to [identify people](https://onlinelibrary.wiley.com/doi/abs/10.1002/widm.1278) and systematically [detain them](https://www.buzzfeednews.com/article/meghara/china-new-internment-camps-xinjiang-uighurs-muslims), ["aggression" detection microphones in schools](https://features.propublica.org/aggression-detector/the-unproven-invasive-surveillance-technology-schools-are-using-to-monitor-students/), and many others. It has never been more clear that **we need to talk about the real world impacts of our work, and consider how our creations are used.** If nothing else, an afternoon would be well spent reviewing the prescient novel [Frankenstein](https://library.oapen.org/bitstream/id/24cb1da5-a512-4de1-b24c-639b6452dbec/628778.pdf), and to consider what you birth into our world.

Like any tool, data-driven technologies are indifferent to the morality of their ends. Perhaps the greatest risk of all is leaving this tool in the hands of the few expensively-educated people who cannot possibly represent all people. To balance this, we seek to lower the barriers to education for all people. Data science and data literacy must be widespread, accessible, and leveraged for building our collective future. More than ever, we need that future to be built by members of society who are diverse and focused on generative, resilient solutions.

> Computers reflect the biases and belief systems of the people programming them 
> 
> -- [@alicegoldfuss](https://twitter.com/alicegoldfuss/status/1016034359134941184)

The OSDSM is built with the belief that **open source education enables the possibility for a diverse, collective, generative future-building.** I hope that you are one of the next Data Scientists to make a difference in the world by helping us all make better decisions with the scientific process and critical thinking. This rewritten curriculum focuses on what is needed to be successful in the entry-level role, but I hope it extends far beyond that.

## The Open Source Data Science Masters

The open-source curriculum for learning to be a Data Scientist. Curriculum resources from both universities and working Data Scientists focuses on foundational theory and applied skills. The OSDSM is collectively-maintained and open to PRs.

The goal of this curriculum is to prepare the student for an entry level Data Scientist role, using open source materials at no cost. The Masters is self-guided and self-accredited. To support this, the structure now includes a Capstone project to demonstrate the student's problem solving approach, skills in execution, and communication. Upon completion, the student can award oneself a Credential on LinkedIn.

This is called a "Masters" because it is primarily geared toward learners with some college-level education in mathematics, programming, economics, or related disciplines. Come as you are!

1. **The Core** - This is a critical foundation for what is to come; don't skip the foundational lessons.
2. **Specialty** - Choose what is most interesting to you, or most relevant to the work you plan to do.
3. **Data Science at Work** - Learn about how doing science with others and for businesses can work.
4. **Capstone Project** - Choose a meaningful project or dataset to demonstrate what you've learned.

![](https://twitter.com/intent/follow?original_referer=https%3A%2F%2Fdeveloper.twitter.com%2F&ref_src=twsrc%5Etfw%7Ctwcamp%5Ebuttonembed%7Ctwterm%5Efollow%7Ctwgr%5ENASA&region=follow_link&screen_name=NASA)

### Motivation

> We’re likely to see more uncredentialed, inexperienced individuals try their hands at data science, **bootstrapping their skills on the open-source ecosystem and using the diversity of modeling tools available.** Just as data-science platforms and tools are proliferating through the magic of open source, big data’s data-scientist pool will as well.

> And there’s yet another trend that will alleviate any talent gap: the democratization of data science. While I agree wholeheartedly with Raden’s statement that “the crème-de-la-crème of data scientists will fill roles in academia, technology vendors, Wall Street, research and government,” I think he’s understating the extent to which **autodidacts – the self-taught, uncredentialed, data-passionate people – will come to play a significant role in many organizations’ data science initiatives.**

-- James Kobielus, [Closing the Talent Gap](http://bit.ly/closingthetalentgap) 17 Jan 2013

### A Note About Direction
This is an introduction geared toward those with at least **a minimum understanding of programming**, and (perhaps obviously) an interest in the components of Data Science (like statistics and distributed computing). The original curriculum is geared toward **Python tools and resources**.
***

## The Open Source Data Science Curriculum

# Start here.

### Intro to Data Science
Get acquainted with the challenge, terminology, technology, statistics, communication, and day-to-day of the Data Scientist.

 1. READ The Signal and The Noise / Nate Silver [Book ```$18```](https://bookshop.org/a/2958/9780143125082) -- Narrative case studies of Data Science.
 2. TRY Python Data Science Handbook: Essential Tools for Working with Data [Book ```$60```](https://bookshop.org/a/2958/9781491912058) -- Jump right into Python as the core tool for doing Data Science `pip install numpy pandas jupyter sklearn`
 3. WATCH Intro to Data Science / University of Washington [Lectures](https://www.youtube.com/playlist?list=PLMiChZq0IHh1A5mz4o0T_vWXJnsi-7EY-)
 4. WITNESS The Life of a Data Scientist / Josh Wills [Video](https://www.youtube.com/watch?v=h9vQIPfe2uU)

#### **Problem Solving**
 * Problem-Solving Heuristics "How To Solve It" George Pólya [Berkeley / Summary](https://math.berkeley.edu/~gmelvin/polya.pdf) [Book ```$18```](https://bookshop.org/a/2958/9780691164076)

#### **Linear Algebra & Programming**
 * Linear Algebra [Khan Academy / Videos](http://bit.ly/khanlinalg)
 * Linear Algebra / Levandosky [Stanford / Book ```$38```](https://bookshop.org/a/2958/9780536667472)
 * Linear Programming (Math 407) [University of Washington / Course](http://bit.ly/course-uw-linearprogramming)
 * The Manga Guide to Linear Algebra [Book ```$19```](http://amzn.to/1n4hM5l)
 * An Intuitive Guide to Linear Algebra [Better Explained / Article](https://betterexplained.com/articles/linear-algebra-guide/)
 * A Programmer's Intuition for Matrix Multiplication [Better Explained / Article](https://betterexplained.com/articles/matrix-multiplication/)
 * Vector Calculus: Understanding the Cross Product [Better Explained / Article](https://betterexplained.com/articles/cross-product/)
 * Vector Calculus: Understanding the Dot Product [Better Explained / Article](https://betterexplained.com/articles/vector-calculus-understanding-the-dot-product/)

#### **Statistics: Frequentist & Bayesian**
`pip install numpy pandas statsmodels`

 * Stats in a Nutshell [Book ```$29```](http://amzn.to/1iMnx2X)
 * Think Stats: Probability and Statistics for Programmers [Digital](http://bit.ly/ebook-thinkstats) & [Book ```$25```](http://amzn.to/RcVnTf)
 * Think Bayes [Digital](http://bit.ly/ebook-thinkbayes) & [Book ```$25```](http://amzn.to/1hmy4Cr)

#### **Statistics: Causation**

`pip install numpy pandas (causalinference)[https://pypi.org/project/CausalInference/]`

A branch of statistics that uses graphical models and specialized statistics to describe and model cause and effect. Editor: Something to watch closely, this is evolving with new capabilities resulting from modeling with big data.

 * Causal Inference in Statistics [Book ```$25```](https://amzn.to/2RiTxmq)
 * The Book of Why [Book ```$22```](https://amzn.to/2Ac3hoQ)

#### **Convex Optimization**
 * Convex Optimization / Boyd [Stanford / Lectures](http://stanford.edu/class/ee364a/index.html) / [Book](http://stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)

#### **Differential Equations & Calculus**
 * Differential Equations in Data Science [Python Tutorial](http://bit.ly/ipynb-differentialeq)

#### **Algorithms**
 * Algorithms Design & Analysis I [Stanford / Coursera](http://bit.ly/coursera-algo)
 * Algorithm Design, Kleinberg & Tardos [Book ```$125```](http://amzn.to/1iMnWm5)

#### **Distributed Computing**
 * _add new_

#### **Databases**
 * Introduction to Databases [Stanford / Online Course](https://bit.ly/introdatabases)
 * SQL School [Mode Analytics / Tutorials](http://bit.ly/sqlschool)
 * SQL Tutorials [SQLZOO / Tutorials](http://bit.ly/tut-sqlzoo)

#### **Data Mining**
 * Mining Massive Data Sets / Stanford [Coures & Digital Textbook](http://bit.ly/mmds-course) & [Book ```$58```](http://amzn.to/1txocpo)
 * Mining The Social Web [Book ```$30```](http://amzn.to/1mqxAsB)
 * Introduction to Information Retrieval / Stanford [Digital](http://bit.ly/ebook-stanford-inforetrieval) & [Book ```$56```](http://amzn.to/1mWbnUT)

#### **Social Network & Graph Analysis**
`pip install networkx`

 * Social and Economic Networks: Models and Analysis / [Stanford / Coursera](http://bit.ly/stanford-socialeconnetworks)
 * Social Network Analysis for Startups [Book ```$22```](http://amzn.to/1jySCCT)

#### **Data Design & Processing**
`pip install apache-airflow`

How does the real world get translated into data? How should one structure that data to make it understandable and usable? Extends beyond database design to usability of schemas and models.
 * [Tidy Data in Python](http://www.jeannicholashould.com/tidy-data-in-python.html)
 * [Functional Data Engineering — a modern paradigm for batch data processing / Maxime Beauchemin](https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a)
 * _need tutorial for Airflow, Maxime's blog posts_

### **Machine Learning**
`pip install -U scikit-learn matplotlib pandas numpy`

 * Machine Learning [Ng Stanford / Coursera](http://bit.ly/stanford-ml) & [Stanford CS 229](http://bit.ly/stanfordcs229)
 * A Course in Machine Learning [UMD / Digital Book](http://bit.ly/22WyV3N)
 * The Elements of Statistical Learning / Stanford [Digital](http://bit.ly/ebook-elemstatlearn) & [Book ```$80```](http://amzn.to/1hmyKry) & [Study Group](http://www.reddit.com/r/eosl)
 * Machine Learning [Caltech / Edx](http://bit.ly/caltech-ml)
 * Programming Collective Intelligence [Book ```$27```](http://amzn.to/1mqxYqW)
 * Machine Learning for Hackers [ipynb / digital book](http://bit.ly/mlforhackers)
 * Intro to scikit-learn, SciPy2013 [youtube tutorials](http://bit.ly/scikit-video-tuts)

### **Probabilistic Modeling**
 * Probabilistic Programming and Bayesian Methods for Hackers [Github / Tutorials](http://bit.ly/ipnb-probabilisticprogramming)
 * Probabilistic Graphical Models [Stanford / Coursera](http://bit.ly/stanford-pgm)

#### **Deep Learning (Neural Networks)**

 * Neural Networks [Andrej Karpathy / Python Walkthrough](http://bit.ly/karpathyneuralnets)
 * Neural Networks [U Toronto / Coursera](http://bit.ly/utoronto-neuralnets)
 * Deep Learning for Natural Language Processing CS224d [Stanford](http://cs224d.stanford.edu/syllabus.html)

#### **Natural Language Processing**
`pip install -U nltk`

 * From Languages to Information / Stanford CS147 [Materials](http://bit.ly/nlpcs124)
 * NLP with Python (NLTK library) [Digital](http://bit.ly/ebook-nltk), [Book ```$36```](http://amzn.to/1iMrDIp)
 * How to Write a Spelling Correcter / Norvig (Tutorial)[http://norvig.com/spell-correct.html]

### Data Analysis
`pip install numpy pandas`

One of the "unteachable" skills of data science is an intuition for analysis. What constitutes valuable, achievable, and well-designed analysis is extremely dependent on context and ends at hand.

 * [numpy Tutorial / Stanford CS231N](http://cs231n.github.io/python-numpy-tutorial/)
 * [Pandas Cookbook](http://bit.ly/jvnspandascookbook)
 * Data Analysis in Python [Tutorial](http://bit.ly/mode-python-tutorials)
 * Big Data Analysis with Twitter [UC Berkeley / Lectures](http://bit.ly/cal-course-bigdatatwitter)
 * Exploratory Data Analysis [Tukey / Book ```$81```](http://amzn.to/1kNUEPa)
 * Python for Data Analysis [Book ```$24```](http://amzn.to/Q2pI5I)

### Designing Machine Intelligence Systems

* Machine Learning: The High-Interest Credit Card of Technical Debt [Paper](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43146.pdf)

### Data Communication and Design

#### **Effective Communication & Storytelling**
* LEADERSHIP LAB: The Craft of Writing Effectively [UChicago / Video](https://buomsoo-kim.github.io/learning/2020/03/30/Craft-of-writing-effectively.md/)

#### **Visualization**

 _Data Visualization and Communication_
 * The Truthful Art: Data, Charts, and Maps for Communication [Cairo / Book ```$21```](http://amzn.to/1UydGAc)

 _Theoretical Design of Information_

 * Envisioning Information [Tufte / Book ```$36```](http://amzn.to/Sn0QI4)
 * The Visual Display of Quantitative Information [Tufte / Book ```$27```](http://amzn.to/1q5FB91)

 _Applied Design of Information_
 * Information Dashboard Design: Displaying Data for At-a-Glance Monitoring [Stephen Few / Book ```$29```](http://amzn.to/1Vwz21v)

 _Theoretical Courses / Design & Visualization_

 * Data Visualization [University of Washington / Slides & Resources](http://bit.ly/uw-dataviz)
 * Berkeley's Viz Class [UC Berkeley / Course Docs](http://bit.ly/cal-viz)
 * Rice University's Data Viz class [Rice University / Slides](http://bit.ly/riceu-viz)

 _Practical Visualization Resources_

 * D3 Library / Scott Murray [Blog / Tutorials](http://bit.ly/tut-scottmurray-d3)
 * Interactive Data Visualization for the Web / Scott Murray [Online Book](http://bit.ly/interactive-data-viz-web) & [Book `$26`](http://amzn.to/1oK1xCN)

#### **Python** Learning
 * Learn Python the Hard Way [Digital](http://bit.ly/ebook-learnpyhardway) & [Book ```$23```](http://amzn.to/1hmzGw9)
 * Python [Class / Google](http://bit.ly/T4j40A)
 * Think Python [Digital](http://bit.ly/ebook-thinkpy) & [Book ```$34```](http://amzn.to/1ktQ5ZU)
 
#### **Python** Environment & Libraries
 * Help installing Basic Packages: [Python, virtualenv, NumPy, SciPy, matplotlib and IPython ](http://bit.ly/scientific-py-install)
 * For scientific uses: [Using Python Scientifically](http://bit.ly/lecture-scipy) & [Command Line Install Script](https://github.com/fonnesbeck/ScipySuperpack) for Scientific Python Packages

_More Libraries can be found in the ["awesome machine learning"](https://github.com/josephmisiti/awesome-machine-learning#python) repo_

#### **Python** (Libraries)

#### **Data Structures & Analysis Packages**
   * Flexible and powerful data analysis / manipulation library with labeled data structures objects, statistical functions, etc [pandas](http://bit.ly/py-pandas) & Tutorials [Python for Data Analysis / Book](http://amzn.to/Q2pI5I)

#### **Machine Learning Packages**
   * [scikit-learn](http://bit.ly/py-scikit) - Tools for Data Mining & Analysis

#### **Networks Packages**
   * [networkx](http://bit.ly/py-networkx) - Network Modeling & Viz

#### **Statistical Packages**
   * [PyMC](http://bit.ly/py-pymc) - Bayesian Inference & Markov Chain Monte Carlo sampling toolkit
   * [Statsmodels](http://bit.ly/py-statsmodel) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests
   * [PyMVPA](http://bit.ly/py-mvpa) - Multivariate Pattern Analysis in Python

#### **Natural Language Processing & Understanding**
   * 
   * [Gensim](http://bit.ly/py-gensim) - Python library for topic modeling, document indexing and similarity retrieval with large corpora. Target audience is the natural language processing (NLP) and information retrieval (IR) community.

#### **Data APIs**
   * [twython](http://bit.ly/py-twython) - Python wrapper for the Twitter API

#### **Visualization Packages**
   * [matplotlib](http://bit.ly/matplotlib-docs) - well-integrated with analysis and data manipulation packages like numpy and pandas
   * [Seaborn](http://bit.ly/seaborn-python) - a high-level statistical visualization package built on top of matplotlib

#### **iPython Data Science Notebooks**
 * [Data Science in IPython Notebooks](http://bit.ly/ipynb-ds) (Linear Regression, Logistic Regression, Random Forests, K-Means Clustering)
 * [A Gallery of Interesting IPython Notebooks - Pandas for Data Analysis](http://bit.ly/ipyfordataanalysis)

#### Datasets are now [here](http://bit.ly/osdsm-datasets-link)

#### R resources are now [here](http://bit.ly/osdsm-rresources)

***

### Data Science as a Profession

> Data Team #squadgoals with [metrics]:
 
> Data Science = Improve decision making [ROI, NPV, IRR], create Hypotheses [business mechanisms]
 
> Data Platform / Engineering = Engineer data to the product [internal and/or customer trust of data metrics]

> Data Product / Research Science = Design and deliver strategic use of data [revenue or product metrics], Disprove Hypotheses [business mechanisms]

_Data Science_, especially in the moment when its moniker rose to prominence, was considered to be a lone wolf sport. The last 5 years have proven not only that **Data Science is a team sport**, but that Data Science requires leadership, tech transformation, and execution follow-through. The best and most impactful work done in Data Science, much like in other domains, is the product of collaboration between people of many different specialties. I've bucketed the most discretely defined functions, which as we all know, are in reality much more blurred in definition. 

In order to win friends and influence people, I suggest thinking deliberately about contributors' **strengths** and **impact** in terms of domain (problem space) and role (solution space). Effective teamwork is dependent on framing the right problem, then leveraging each others' strengths to solve together. Teamwork makes the dream work!

#### 1) Analytics 
**Goal: Build business knowledge and advise decision-making.**

This group uses analytical thinking, data manipulation, and business sense to analyze and advise the business on its goals and objectives. This group typically does not build software or scalable assets. Data Scientists may prototype fact_ tables (and other assets) which Data Engineering then enables to be scalably and consistently produced.

_Classic example: Data Scientist uses analysis to better understand growth and churn of different customer segments_

#### 2) Product / Research Science 
**Goal: Experiment to learn.**

A Research Scientist uses the scientific method to validate the value of a change in process or product. They will come up with an idea of how to model a real world phenomenon, then validate through experimental methods.

_Classic example: Research Scientist builds experimental methods to estimate the acceptance or rejection of new features across the user base_

#### 3) Intelligence Engineering 
**Goal: Build and grow intelligent applications and products.**

Machine Intelligence Engineers play a role at the intersection of science and scale. They are responsible for engineering algorithmic and statistical machinery at scale to satisfy customer needs and experience.

_Classic Example: NLP Engineer who improves language translations using neural networks and a combination of reference texts and behavioral data like repeated queries_

#### 4) Data Design & Engineering 
**Goal: Define how the real world is encoded in data.**

Data Engineering entails designing the production and maintenance of data such that it most accurately reflects the world being modeled by Data Scientists, Research Scientists, and Intelligence Engineers. They may take data models which Analysts have prototyped and turn them into living data assets. Data Design is always evolving and never "done".

_Classic Example: Data Engineer builds data flows from events to produced fact\_ tables, which reflect the bookings made across the company and their sources_

### Ethics in Data Science & Machine Intelligence
Human impact is a first-class concern when building machine intelligence technology. When we build products, we deduce patterns and then reinforce them in the world. Ethics in any Engineering concerns understanding the sociotechnological impact of the products and services we are bringing to bear in the human world -- and whether they are reinforcing a future we all want to live in.
* [Index: Cultural Bias in Machine Intelligence](http://machinebias.org/)

### Data Science Across Domains

**Huge Disclaimer:** You can "Data Science" almost _anything_. This captures a high level view of how Data Science is being applied in a handful of domains. Use your new-found data science chops!

| Domain | Problem Space | 
| -- | -- | -- | -- |
| **Risk & Economic Modeling** | | | |
| Is this person who they say they are? | Financial & Identity Risk | 
| Which customers to target with this Ad? | Customer Targeting and Ads Applications | 
| What credit terms to assign this consumer? | Creditworthiness | 
| Price of a given thing? | Econometrics and Price Modeling | 
| What observable factors predict patient risk of a given adverse condition? | Healthcare Risk Modeling and Projections | 
| What might the range of effects of upcoming policy be? | Policy Simulation | 
| Where might the next natural disaster occur? | 
| How might we assign risk to high-impact, rare events? | Surveillance Platforms | 
| | | |
| **Features & Optimization** | | | |
| What information is relevant? | Information Extraction, Structuring Applications, NLP | Google knowledge graph and similar teams | |
| What else would this consumer likely buy? | Recommendations | 
| When and where will traffic happen? | Transportation | 
| How might we optimize supply chain throughput, bandwidth, marginal profit? | Supply Chain and Ops Mgmt | 
| | | |
| **[Data Journalism](https://datajournalismhandbook.org/1.0/en/index.html)** | 
| What evidence can be derived from available data? | 
| | | |
| **Consulting** | Management Consulting and Software Consulting | 
| | | |
| **Platform Tooling** | Analytics, Infrastructure, Platform Tools | 
| Is this hypothesis valid? | Experimentation, AB Testing |

Please PR your ideas, even if no company known to humans does the thing you're thinking of.

#### Advice from Professionals
 * Doing Data Science: Straight Talk from the Frontline [O'Reilly / Book ```$25```](http://amzn.to/1vAIscK)
 * The Data Science Handbook: Advice and Insights from 25 Amazing Data Scientists [Book ```$22```](http://amzn.to/1J7lILJ)

### Capstone Project
* Capstone Analysis of Your Own Design; [Quora](http://bit.ly/quora-toyproblems)'s Idea Compendium
* Healthcare Twitter Analysis [Coursolve & UW Data Science](http://bit.ly/project-healthcare-twitter-analysis)
* Analyze your LinkedIn Network [Generate & Download Adjacency Matrix](http://socilab.com/)

***

#### `Take Two` Change Log
1. Restructured ala the [2022 Plan](https://docs.google.com/presentation/d/18iSlwSG6F57URqIl47KUmEJCtvS_x4Uxp71caY0-wp8/edit#slide=id.g1196d9e5821_0_0).
2. Pruned broken links. It's been a while, and some of these resources have moved -- or worse -- been taken down.
3. Pared down links to a more opinionated list.
4. Theory + Python tools together under each topic. All you need under one roof.
5. Proceeds. [Bookshop.org](http://bookshop.org) links for all books, which supports independent bookshops with commissions. Since the first commits in 2014, I have donated any related commissions to [Planned Parenthood](https://www.plannedparenthood.org/), which was one of the few healthcare providers in my community growing up and is the largest single provider of reproductive health services in the US. Though donations should flow to independent bookshops from now on, my personal commitment to PP remains.

***

## Contribute

Please Contribute; **this is Open Source!**

[@clarecorthell](http://bit.ly/clarecorthelltwitter)

_RIP [v1.0 commit](https://github.com/datasciencemasters/go/tree/d6cec020ac3d038cd787e9a779a3cea188c779f2)_
