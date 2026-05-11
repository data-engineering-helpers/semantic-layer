# Knowledge sharing - Semantic layer

## Table of Content (ToC)

* [Knowledge sharing \- Semantic layer](#knowledge-sharing---semantic-layer)
  * [Table of Content (ToC)](#table-of-content-toc)
  * [Overview](#overview)
    * [Other repositories of Data Engineering helpers](#other-repositories-of-data-engineering-helpers)
  * [References](#references)
    * [Ontology](#ontology)
  * [Articles](#articles)
    * [How to build a semantic layer, step by step](#how-to-build-a-semantic-layer-step-by-step)
    * [Databricks friendly analytics pipeline for startup folks and learners](#databricks-friendly-analytics-pipeline-for-startup-folks-and-learners)
    * [Practical Guide to Semantic Layers](#practical-guide-to-semantic-layers)
    * [Unlocking the Power of Data in Biopharma](#unlocking-the-power-of-data-in-biopharma)
    * [BI as code](#bi-as-code)
    * [Build a Semantic Layer on Databricks](#build-a-semantic-layer-on-databricks)
    * [Knowledge mesh and data products](#knowledge-mesh-and-data-products)
    * [What Syntax for the Semantic Layer](#what-syntax-for-the-semantic-layer)
    * [Analytics Heroes by Modern Data 101 with Matthew Weingarten](#analytics-heroes-by-modern-data-101-with-matthew-weingarten)
    * [Metrics\-focused data strategy with model\-first data products](#metrics-focused-data-strategy-with-model-first-data-products)
    * [Semantic layers \- A buyers guide](#semantic-layers---a-buyers-guide)
    * [The Semantic Layer Movement: The Rise &amp; Current State](#the-semantic-layer-movement-the-rise--current-state)
    * [Making Sense of the Semantic Layer](#making-sense-of-the-semantic-layer)
  * [Solutions](#solutions)
    * [Boring semantic layer](#boring-semantic-layer)
    * [Metalayer](#metalayer)
    * [Cube](#cube)
    * [Denodo](#denodo)
    * [MetricFlow](#metricflow)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

## Overview

[This project](https://github.com/data-engineering-helpers/semantic-layer)
intends to document requirements and referential material about
the semantic layer (_e.g._, metrics, business rules)
in the perspective of data engineering on a modern data stack (MDS).
The semantic layer is also sometimes referred to as
[ontology](https://en.wikipedia.org/wiki/Ontology_(information_science)).

Even though the members of the GitHub organization may be employed by
some companies, they speak on their personal behalf and do not represent
these companies.

### Other repositories of Data Engineering helpers

* [Data Engineering Helpers - Knowledge Sharing - Data products](https://github.com/data-engineering-helpers/data-products)
* [Data Engineering Helpers - Knowledge Sharing - Data contracts](https://github.com/data-engineering-helpers/data-contracts)
* [Data Engineering Helpers - Knowledge Sharing - Data quality](https://github.com/data-engineering-helpers/data-quality)
* [Data Engineering Helpers - Knowledge Sharing - Architecture principles](https://github.com/data-engineering-helpers/architecture-principles)
* [Data Engineering Helpers - Knowledge Sharing - Data life cycle](https://github.com/data-engineering-helpers/data-life-cycle)
* [Data Engineering Helpers - Knowledge Sharing - Data management](https://github.com/data-engineering-helpers/data-management)
* [Data Engineering Helpers - Knowledge Sharing - Data lakehouse](https://github.com/data-engineering-helpers/data-lakehouse)
* [Data Engineering Helpers - Knowledge Sharing - Metadata](https://github.com/data-engineering-helpers/metadata)
* [Data Engineering Helpers - Knowledge Sharing - Data pipeline deployment](https://github.com/data-engineering-helpers/data-pipeline-deployment)

## References

### Ontology

* [Wikipedia - Ontology (information science)](https://en.wikipedia.org/wiki/Ontology_(information_science))

> More simply, an ontology is a way of showing the properties of a subject area
> and how they are related, by defining a set of terms and relational
> expressions that represent the entities in that subject area.

## Articles

### How to build a semantic layer, step by step

* [LinkedIn post - How to build a semantic layer, step by step](https://www.linkedin.com/pulse/how-build-semantic-layer-step-by-step-guide-alex-merced-gcjje/)
  * Author: [Alex Merced](https://www.linkedin.com/in/alexmerced/)
  * Date: May 2026

### Databricks friendly analytics pipeline for startup folks and learners

* Author: [Luis Lopez Pons](https://www.linkedin.com/in/luislopezpons/)
* Date: Nov. 2025
* [LinkedIn post](https://www.linkedin.com/posts/luislopezpons_erp-growthmetrics-mrr-activity-7394297915852341248-PVY8/)
* [GitHub repository](https://github.com/Caliu-Data/databricks-startups-metrics/)

### Practical Guide to Semantic Layers

* Title: Practical Guide to Semantic Layers: From Definition to Demo
* Author: Rasmus Engelbrecht
  ([Rasmus Engelbrecht on LinkedIn](https://www.linkedin.com/in/rasmusengelbrechtsorensen/),
  [Rasmus Engelbrecht on Substack](https://substack.com/@rasmusengelbrecht))
* Date: Oct. 2025
* [Blog post on Substack](https://rasmusengelbrecht.substack.com/p/practical-guide-to-semantic-layers)

### Unlocking the Power of Data in Biopharma

* Title: Unlocking the Power of Data in Biopharma: Why a Semantic Layer (Finally)
  Makes It Click
* Date: Aug. 2025
* Author: Nnaemezue (Mezue) Obi-Eyisi
  ([Nnaemezue Obi-Eyisi on LinkedIn](https://www.linkedin.com/in/nobieyisi/),
  [Nnaemezue Obi-Eyisi on Medium](https://afroinfotech.medium.com/))
* [Blog post on Medium](https://afroinfotech.medium.com/unlocking-the-power-of-data-in-biopharma-why-a-semantic-layer-finally-makes-it-click-b179d4e88208)

### BI as code

* Date: Aug. 2025
* Author: Matt Martin
  ([Matt Martin on LinkedIn](https://www.linkedin.com/in/mattmartin14/),
  [Matt Martin's blog on Substack](https://substack.com/@performancede))
* [Link to the post on LinkedIn](https://www.linkedin.com/posts/mattmartin14_duckdb-dataengineering-copilot-activity-7362431315020771328-OcDk/)
* Verbatim:

> I am finding that I'm starting to do a lot more charting in python notebooks
> now than I used to; reason being is its brain-dead easy to just put a quick
> prompt on copilot to build you something. As an example, if I have a duckdb
> query working for me and I want to chart the results, I can with this simple
> copilot prompt in the cell:
> "create a bar chart with matplotlib that shows order counts by month; add a
> trend line showing the average order count by month".
> In the screenshot below, you will notice that copilot is smart enough
> to interpret my natural language prompt and examine the SQL statement
> above and match my request to the actual fields (I did not have to provide
> a mapping whatsoever). This is literally done in less than a couple seconds
> and I did not have to go crack open another BI tool like Tableau.
>
> This is been accelerating my Q/A of datasets much faster now; I'm finding less
> and less a need for traditional BI tools going forward.

### Build a Semantic Layer on Databricks

* Title: Can You Build a Semantic Layer on Databricks Without a Third-Party Tool?
* Date: Jul. 2025
* Author: Nnaemezue (Mezue) Obi-Eyisi
  ([Nnaemezue Obi-Eyisi on LinkedIn](https://www.linkedin.com/in/nobieyisi/),
  [Nnaemezue Obi-Eyisi on Medium](https://afroinfotech.medium.com/))
* [Blog post on Medium](https://afroinfotech.medium.com/unlocking-the-power-of-data-in-biopharma-why-a-semantic-layer-finally-makes-it-click-b179d4e88208)
* [Post on LinkedIn](https://www.linkedin.com/posts/nobieyisi_can-you-build-a-semantic-layer-on-databricks-activity-7349061083174772770-nt17/)

### Knowledge mesh and data products

* Title: Knowledge mesh and data products
* Date: Mar. 2025
* Author: Andrea Gioia
  ([Andrea Gioia on LinkedIn](https://www.linkedin.com/in/andreagioia/))
* [Link to the post on LinkedIn](https://www.linkedin.com/posts/andreagioia_thedatajoy-dataproducts-ontology-activity-7303666970078449664-shYT)

### What Syntax for the Semantic Layer

* Title: What Syntax for the Semantic Layer
* Date: Mar. 2025
* Author: Benoit Pimpaud
  ([Benoit Pimpaud on LinkedIn](https://www.linkedin.com/in/pimpaudben/),
  [Benoit Pimpaud on Medium](https://medium.pimpaudben.fr/))
* [Link to the article on Medium](https://medium.pimpaudben.fr/what-syntax-for-the-semantic-layer-9cbc30976609)

### Analytics Heroes by Modern Data 101 with Matthew Weingarten

* Title: Analytics Heroes by Modern Data 101 with Matthew Weingarten
* Date: Jan. 2025
* Author: Matt Weingarten
  ([Matt Weingarten on LinkedIn](https://www.linkedin.com/in/matthewweingarten201/),
  [Matt Weingarten on Medium](https://medium.com/@matt_weingarten))
* Hosted by: Abhyudai Verma
  ([Abhyudai Verma on LinkedIn](https://www.linkedin.com/in/abhyudai-verma/))
* [Link to the article on LinkedIn](https://www.linkedin.com/posts/modern-data-101_matt-analytics-heroes-slider-activity-7291045398675181568-RGye)
* [Link to the introduction on Modern Data 101](https://www.moderndata101.com/analytics-heroes/matthew-weingarten)
  * [Link to the video on Youtube](https://youtu.be/ZYWMGMgoyYw)

### Metrics-focused data strategy with model-first data products

* Title: Metrics-Focused Data Strategy with Model-First Data Products
* Authors: Animesh Kumar, Shubhanshu Jain, Samadrita Ghosh, and Nikhil Singh
* Date: 28 March 2024
* [Article on Substack](https://moderndata101.substack.com/p/model-first-data-products)

### Semantic layers - A buyers guide

* Title: Semantic Layers: A Buyers Guide
* Authors: David Jayatillake and Rohan Thakur
* Date: 25 March 2024
* [Link to the article on Substack](https://davidsj.substack.com/p/semantic-layers-a-buyers-guide)

### The Semantic Layer Movement: The Rise & Current State

* Title: The Semantic Layer Movement: The Rise & Current State
* Date: Oct. 2024
* Author: [Animesh Kumar](https://www.linkedin.com/in/anismiles/)
* [Link to the article on Medium:](https://medium.com/@community_md101/the-semantic-layer-movement-the-rise-current-state-f8dbbb989b2e)

### Making Sense of the Semantic Layer

* That is one of the seminal articles starting the concept of Semantic layer
* Title: Design Tip #158 Making Sense of the Semantic Layer
* Date: Aug. 2013
* Author: Joy Mundi
  (she has retired long ago by now;
  [Joy Mundi on the Kimball Group site](https://www.kimballgroup.com/author/joy/),
  [Joy Mundi on LinkedIn](https://www.linkedin.com/in/joy-mundy-226bb1/))
* [Link to the Kimball Group post](https://www.kimballgroup.com/2013/08/design-tip-158-making-sense-of-the-semantic-layer/)

## Solutions

### Boring semantic layer

* [GitHub - Boring Semantic layer](https://github.com/boringdata/boring-semantic-layer)
* Main contributors:
  * Julien Hurault
    ([Julien Hurault on LinkedIn](https://www.linkedin.com/in/julienhuraultanalytics/),
    [Julien Hurault on Substack](https://substack.com/@juhache))
  * David Krevitt
    ([David Krevitt on LinkedIn](https://www.linkedin.com/in/david-krevitt-a11b8a50/),
    [David Krevitt on Substack](https://substack.com/@davidkrevitt))
* [Article on Substack](https://juhache.substack.com/p/the-boring-semantic-layer)

### Metalayer

* [LinkedIn post](https://www.linkedin.com/posts/janssenryan_what-if-your-semantic-layer-was-just-a-folder-activity-7450280634452750337-iyTn/)
* Author: Ryan Janssen
  ([Ryan Janssen on LinkedIn](https://www.linkedin.com/in/janssenryan/),
  [Ryan Janssen on GitHub](https://github.com/ryanjanssen))
* [Metalayer home page](https://www.metalayer.md/)
* [GitHub - Metalayer](https://github.com/ryanjanssen/metalayer)
* Overview:

> A self-learning context layer for data analytics. It's a `[[wiki-linked]]`
> folder of markdown files.
> MetaLayer is a plugin that helps your agents query data. It makes their
> answers more consistent and less prone to error by capturing metrics, joins,
> and other lore about your data warehouse

### Cube

* [Cube - Home page](https://cube.dev)
* [GitHub - Cube repository](https://github.com/cube-js/cube)
* Statement: Cube — Universal semantic layer platform for AI, BI, spreadsheets,
  and embedded analytics

> Cube is the semantic layer for building data applications. It helps data
> engineers and application developers access data from modern data stores,
> organize it into consistent definitions, and deliver it to every application.
> Cube was designed to work with all SQL-enabled data sources, including cloud
> data warehouses like Snowflake or Google BigQuery, query engines like Presto
> or Amazon Athena, and application databases like Postgres. Cube has a built-in
> relational caching engine to provide sub-second latency and high concurrency
> for API requests.

### Denodo

* [Home page](https://www.denodo.com/en)
* Statement: "One Logical Platform for All Your Data One Modern Solution for
  Your Business"

### MetricFlow

* [GitHub repository](https://github.com/dbt-labs/metricflow)
* Statement: "MetricFlow is a semantic layer that makes it easy to organize
  metric definitions"
