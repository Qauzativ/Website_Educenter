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
category: ""
# teacher
teacher: ""
# duration
duration: ""
# weekly
weekly: ""
# course fee
fee: ""
# apply url
apply_url : "#"
# type
type: "product" # "course" # "research" # "event" # "notice" # "scholarship" # "post" # "deliverables"
---

Qauzativ Community is an open source datawarehouse that ingests, cleanses,
pre-processes, augments data from credit / insurance bureau reports, ERP, CRM,
generates features for predictive modeling, with a focus on credit risk,
insurance, and retail analytics.

***

### What problem it solves

Data driven business operations start with data.
A good old "classic" datawarehouse or a bigdata-ready datalake is required
to consolidate various dataflows and prepare the data for predictive modeling.

QZ Community can be a good use as:

* a specialized datamart for data analytics in an existing ecosystem
* a central datawarehouse or a testing ground for DSML projects

It can be used to manage commercially sensitive or personal data in-house,
and to export de-personalized data snapshots to advanced data analytics tools
in Azure, AWS, Google Cloud and alike.
That would resolve cross-border data movement regulations such as personal
data protection that may exist.

***

### Why use it

Here are a few reasons to consider:

#### It is free and open source

QZ Community is licensed under the Creative Commons license.
We encourage and appreciate community contribution to the source code.

The freely available SQL Server Developer edition works perfect for testing
and customizing your QZ Community installation.
If it is meant to function as a mid-sized datamart for data processing,
Express or Standard editions will work just fine.
For big and diverse data and for in-database application of ML algorithms,
the Enterprise edition is required.

#### Fast, efficient and ubiquitous

Ample performance and usability advantages come from SQL Server's ability
to run R / Python algorithms in-database directly on the data with low latency.

SQL Server has been one of the most popular database management systems
for decades; it is battle-tested and trusted by millions around the globe.
That makes SQL Server developers and administrators much easier to find
than engineers for less known bigdata platforms.

#### Turn historic costs into an asset

QZ Community gets more capable with every credit / insurance bureau report
loaded into it. On top of that comes ERP and CRM data that no one knows better
than you, making your predictive models more precise and fine-tuned than
generic 3rd party models.

The money spent on bureau reports over the years turns into a digital asset
that generates input for company-wide DSML data flows.

#### Single source of truth

The core database schema conforms to the
[3NF normalization](https://en.wikipedia.org/wiki/Third_normal_form);
some additional datastores are
[2NF normalized](https://en.wikipedia.org/wiki/Second_normal_form).

That makes addition of new data sources as easy as importing a new table with
a few mouse clicks, and creates a convenient platform that consolidates
data sources into a
[**single source of truth**](https://en.wikipedia.org/wiki/Single_source_of_truth).

#### ML and big data ready

While the core data is structured and normalized, a QZ Community installation
extends to big and unstructured data by leveraging SQL Server Big Data Clusters
and exchanging data with HDFS (i.e. Hadoop apps), MongoDB, and many more
external data sources.
Should you want to add less structured data from SQL Server Big Data Clusters
to the core DW schema alongside structured / relational data sources,
perform 2NF normalization prior to adding that data as additional tables.

***

Last but not least, in case we discontinue this product or go out of business,
you retain the source code and keep using it, no strings attached.

***

### How it works

QZ Community provides a set of starting functionality in a number of steps:

* Credit / insurance bureau reports are parsed and loaded into 3NF normalized tables

* 20+ data quality checks and fixes are applied; after that the data is
  deduplicated and augmented, e.g. additional data series are generated

* Features (variables) are calculated from cleaned pre-processed data;
  sample predictive models are trained with several ML algorithms

* Customer-related data from ERP, CRM, and similar applications is combined
  with data from credit / insurance reports;
  the preceding steps can be applied to new data sources in the same fashion

***

More features will be added in the future through community contribution
and from [QZ Cloud](/product/qauzativ_cloud).

The [feature comparison table](/product) provides a brief picture while
[GitHub](https://github.com/Qauzativ) documentation and source code allow for
a deeper insight into the current scope of features.
