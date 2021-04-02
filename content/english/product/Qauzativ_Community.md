---
title: "Qauzativ Community"
# date: 2021-07-06T15:27:17+06:00
draft: false
# page title background image
bg_image: "images/backgrounds/page-title.jpg"
# course thumbnail
image: "images/courses/course-1.jpg"
# meta description
description : ""
# taxonomy
category: "Photography"
# teacher
teacher: "Clark Malik"
# teacher2
teacher2: "Clark Gable"
# duration
duration : "06 Month"
# weekly
weekly : "03 hours"
# course fee
fee : "From: $699"
# apply url
apply_url : "#"
# type
type: "product" # "course" # "research" # "event" # "notice" # "scholarship" # "post" # "deliverables"
---

Qauzativ Community is an open source datawarehouse that ingests, cleanses,
pre-processes, augments data from credit / insurance bureau reports, ERP, CRM,
generates features for predictive modeling, with a focus on credit risk,
insurance and retail analytics.

***

### What problem it solves

Data driven business operations start with data -- require a good old "classic"
datawarehouse or a bigdata-ready datalake to consolidate various dataflows.
Many companies run a few databases that power mission critical applications
and perhaps a few data silos for BI, reporting and data mining purposes.

QZ Community can be put to good use as:

* a specialized datamart for data analytics in an existing ecosystem
* a central datawarehouse or a testing ground for DSML projects

QZ Community can be used to manage commercially sensitive and personal data
in-house and export de-personalized data snapshots to advanced data analytics
tools in Azure, AWS, Google Cloud and alike -- resolving cross-border data
movement regulations, including personal data protection, that may exist.

***

### Why use it

Here are a few reasons to consider:

#### It is free and open source

It is licensed under the Creative Commons license.
All you need is SQL Server Enterprise edition if ML algorithms will be
applied in-database. While testing and customizing, free Developer
edition works perfect to test all potential capabilities.
If the installation is meant to be a simple datamart, Express or Standard
editions will work just fine.

We encourage and apprecaite community contribution to the source code.
In case we discontinue this product or go out of business, you retain
the source code and keep using it, no strings attached.

#### Fast, efficient and ubiquitous

Ample performance and usability advantages come from SQL Server's ability
to run ML algorithms in R or Python code and deploy predictive models into
production directly on the data in-database.

SQL Server has been one of the most popular database management systems
for decades. SQL Server developers and administrators are much easier to find
than engineers for exotic or sophisticated bigdata platforms.

#### Turn historic costs into an asset

QZ Community gets more capable with every credit / insurance bureau report
loaded into it. On top of that comes ERP and CRM data that no one knows better
than you, making your predictive models more precise and fine-tuned than
generic 3rd party models.

The money spent on bureau reports over the years is converted into a digital
asset that generates input for company-wide DSML data flows.

#### Single source of truth

QZ Community's core schema conforms to the
[3NF normalization](https://en.wikipedia.org/wiki/Third_normal_form)
and some internal datastores are
[2NF normalized](https://en.wikipedia.org/wiki/Second_normal_form).

That makes addition of new data sources as easy as importing a new table
with a few mouse clicks and turns QZ Community into is a convenient platform
to consolidate data sources into a [**single source of truth**](https://en.wikipedia.org/wiki/Single_source_of_truth).

#### ML and big data ready

While the core data is structured and normalized, a QZ Community installation
extends to big and unstructured data by leveraging SQL Server Big Data Clusters
and exchanging data with HDFS (i.e. Hadoop apps), MongoDB and many more
external data sources.

Should you want to add less structured data from SQL Server Big Data Clusters
to the core DW schema alongside structured / relational data sources,
perform 2NF normalization prior to adding that data as additional tables.

***

### How it works

QZ Community provides the starting functionality for a number of operations:

* Credit / insurance bureau reports that have accumulated over the years
  will be parsed and loaded into 3NF normalized tables

* The data is submitted to multiple (20+) routine data quality checks and fixes

* Data is deduplicated and augmented, which is actually generating additional
  data series from existing input data

* Features (variables) are generated and then several ML algorithms
  are implemented on that data

* Basic customer-related data from ERP, CRM and similar applications
  is loaded for combining it with credit / insurance data in data analytics

Documentation and source code at [our GitHub page](https://github.com/Qauzativ)
gives a deeper insight into the current scope of features;
the [edition comparison table](/product) provides an overview.

More features will be added in the future through community contribution
and from [QZ Cloud](/product/qauzativ_cloud) edition.
