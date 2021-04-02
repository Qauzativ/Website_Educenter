---
title: "Core DSML track"
# date: 2021-07-06T15:27:17+06:00
draft: false
# page title background image
bg_image: "images/backgrounds/page-title.jpg"
# image
image: "images/courses/course-1.jpg"
# meta description
description: "description of the 'Core ML' track"
# taxonomy
category: "Photography"
# teacher
teacher: "Clark Malik"
# duration
duration: "06 Month"
# weekly
weekly: "03 hours"
# course fee
fee: "From: $699"
# apply url
apply_url: "#"
# download link
download_link: "#"
# type
type: "training" # "course"  # "research" # "event" # "notice" # "deliverables" # "training"
---

The Core DSML track is not yet another machine learning course.
We do not intend to create substitutes for ML programs from
top universities and companies like Udacity, DataCamp, DataQuest.

a series of projects that teach trainees to perform data analysis and
build predictive models.

complementing [DataCamp's](https://www.datacamp.com) online courses

***

### What is "Core DSML track"?

This learning track is a complete solution for credit risk modeling, first of all.
It teaches how to assess credit risk with not only the standard classification
approach but also regressions and survival analysis, hence different target
variables are used -- binary, numeric, time-based -- for thorough assessment.

Secondly, the training is reproducible on other types of machine learning tasks.
The code libraries that we deliver are re-usable for most ML problems except
computer vision, natural language processing and other specific topics.

Trainees learn the essentials of machine learning through extensive practice.
We start with an introduction to statistics, SQL and databases.
Then we practice data manipulation, pre-processing and feature engineering.
Those are essential steps to build high-performing machine learning models.
It is followed by feature selection and model training.
Credit risk modeling is the base 'learner' in the training program;
as mentioned above, we use 'standard' classification for binary default/non-default,
survival analysis to predict time till default and regressions to predict
other quantitative measures of default.
Then we interpret the models with LIME and Shapley values, measure models'
performance, select the best performing ones by analyzing the bias-variance
tradeoff and various evaluation metrics.
Reject inference analysis is performed against real-life cases to minimize
false positive & false negative predictions.

The course provides a sound mix of both theoretical and technical insights and
conforms to a standard curriculum of typical data scientist specializations.
It also delivers practical implementation that lays ground for credit risk modeling
in the context of the Basel and IFRS 9 guidelines.
Trainees will learn necessary tools to assess 3 key credit risk parameters:
Probability of Default (PD), Loss Given Default (LGD), and Exposure at Default (EAD).

***

Core DSML track is composed of 5 interconnected parts:
a sequence of **end-to-end** R / Python tutorials with code for the entire
[CRISP-DM cycle](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)
from data exploration through model interpretation/selection/calibration,
instructor-led labs by DS/ML practitioners,
lectures on the fundamentals of DS/ML theory by university professors,
[DataCamp](https://www.datacamp.com/tracks/career) short interactive online courses,
and practice-based projects.

Optional: we use 1-2 relevant real-life Kaggle competitions as additional
learners alongside the credit risk modeling project by re-engineering
those competitions with customer's data.

***

### What trainees will learn

Trainees learn the 'classic' junior data scientist toolbox:
**{data exploration + visualization + classification + regression}**

Online specializations and skill tracks in DS/ML (see links at the bottom of this page)
that correspond to common definition of the 'junior/middle data scientist'
skillset usually span 6-8 months and require 300-400 hours of studying @ 12-15 hours per week.
Such specializations typically exclude deep learning & big data infrastructure
but sometimes cover additional topics like association rules, recommender systems,
graph analysis or time series modeling.
Our syllabus is similar with few notable differences or enhancements, shall we say.

* Full program duration is 3-3.5 months

* Guided labs by ML practitioners ~2 times / 4 hours per week

* 20-25 lecture hours by university professors on ML fundamentals

* Trainees complete 20+
  [DataCamp](https://www.datacamp.com/tracks/skill) short online courses,
  most of which are part of 'Data Scientist with R / Python' skill tracks

* Model interpretability is the new norm in DS/ML. Still a frontline of DS/ML research,
  it is not yet widely taught in online courses or textbooks. Trainees learn the latest
  [SHAP](https://github.com/slundberg/shap/) and
  [LIME](https://www.oreilly.com/learning/introduction-to-local-interpretable-model-agnostic-explanations-lime)
  techniques to explain 'black box' models

* Special emphasis is placed on the cornerstone concepts of ML:
  bias-variance tradeoff, overfitting and underfitting,
  model selection using performance metics (ROC/AUC, Gini, Sensitivity,
  Specificity, Kappa, RMSE, etc.)

* The following data exploration tasks -- treatment of outliers, anomalies & missing
  values, variable discretization, feature selection (using 6-8
  algorithms) -- are often overlooked in online courses and textbooks but
  covered in detail in our program.

* Credit risk modeling is the base learner in the capstone practice-based project
  * 300+ variables generated in DataStore from XML credit reports

  * Several target variable types reflecting different ways to measure
    credit risk -- 'classic' binary default / non-default, continuous numeric,
    time-based values -- are handled with classification, regression and survival
    analysis models

  * 'Dormant' borrowers who recently took a new loan after prolonged period
    of inactivity are treated as a separate category

  * Borrowers with 2+ loans are another separate category of a higher risk profile

  * Aggregate credit risk of a borrower as a single entity is assessed, i.e.
    probability of default on any of the borrower's outstanding loans

  * Probability of default is also calculated for each loan depending on
    its type, amount, term as well as borrower's overall debt

* Deep learning frameworks (Keras, Tensorflow) are used for model training
  alongside 'conventional' algorithms like boosting, bagging, SVM, etc.

* Reject inference analysis is a highly recommended part of the training

_The following topics -- clustering, association rules, sequence rules, causality,_
_graph/network analysis -- are available as custom training programs upon request._
_They are customized to specific data and business requirements._

***

### What trainees will take away, i.e. our deliverables

* R / Python code libraries are delivered in 2 forms: as executable code inside RMarkdown files
  as well as a 200+ page [pdf/html book](http://127.0.0.1:4321/documentation/online-book/).
* Lecture notes
* ML textbooks
* DataCamp subscriptions for self-study through 300+ courses beyond the syllabus
* Optional: review and re-engineering of relevant Kaggle competitions
* Optional: TeamHub, the codebase & documentation knowledgebase

***

### Pre-requisites

Mathematics or computer science background is not a requirement; trainees
without prior programming experience will learn to write code during the training.
We welcome business domain experts -- risk managers, financial analysts,
marketing & customer service professionals -- to learn DS/ML.

***

### Why Core DSML track?

Core DSML track might be a good match if:

* you need to build a DS/ML team that should have the skills to tackle
  real-life business tasks from 'day 1'
* you consider training employees into data scientists to increase the DS/ML team
* IFRS 9 and Basel regulation calls for more sophisticated credit risk modeling than
  the current one ---> i.e. if full-fledged PD, LGD, EAD modeling is required

And if you believe that:

* it is easier and faster to train 10 business experts in DS/ML rather than
  3-5 data scientists in 10 different business domains
* it is cheaper because the business domain experts are likely your employees,
  hence you depend less on outside hiring and rely more on internal human resources

#### The key reason: it saves time and money

Firstly, trainees are driven by guided training through the syllabus
2x faster than in online 'data scientist' specializations.

Secondly, code re-use is efficient and effective.
It will eventually save you hundreds/thousands of man-hours and thousands of
US$ in labour costs once trainees have learned and start re-using the
standardized code templates that come as part of this learning track.

Thirdly, you will likely depend less on hiring data scientists from outside
because your business domain experts can learn these skills via in-house training
and start contributing valuable data analysis insights to DS/ML projects.
Cross-functional teams will speed up DS/ML adoption by adding
intelligent layers of data-driven decisions across a range of operations.

Our code templates work end-to-end from raw data mining to model interpretation
& selection and contain substantially more re-usable code than online courses.
Data cleaning, exploration and manipulation usually take up to 80% of time in DS/ML.
Those fairly simple activities are often the most expensive ones in terms of
time they consume.

> Shorter model-to-production time = higher ROI on DS/ML investment

Data scientists will no longer have to spend hundreds of hours on writing
code for nearly same recurring tasks on different projects.
No time has to be spent on adaptation of generic coding exercises from
online courses or tutorials, rather trainees start delivering production-grade
solutions by re-using the code templates that they learn during the training.
This will save senior data scientists time to focus on more complex tasks,
share advanced solutions with a DS/ML team, mentor juniors, so that
more things will get done with available resources.

Multiply hundreds and thousands man-hours by labour cost per hour --
that's how much payroll money we can help save, especially when the training
comes with our [TeamHub](http://127.0.0.1:4321/products/teamhub/) solution
for code & documentation sharing.

#### Few more reasons

Please see our FAQ section for more detailed overview of how
Core DSML track delivers value to your business:

* Model interpretability
* Data analytics as a by-product
* Practical implementation of real-life tasks

***
