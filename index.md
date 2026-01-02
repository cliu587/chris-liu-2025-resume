---
layout: cv
title: Chris Liu - Senior Staff Software Engineer and Mathematician
---
# Chris Liu
Senior Staff Software Engineer and Mathematician.

<div id="webaddress">
<a href="chris.cl587@gmail.com">chris.cl587@gmail.com</a>
| <a href="https://www.linkedin.com/in/cl587/">linkedin.com/in/cl587</a>
</div>


## Currently

Math PhD candidate (expected July 2026) seeking software-related roles post-graduation.
My research is on tensors found in mathematics, and in particular, their algebraic invariants.
Two of my contributions are faster algorithms to compute these invariants and proving a local-to-global theorem.

## Previously

Senior Staff Software Engineer at Coursera

Responsibilities included shepherding Coursera's Scala to Java transition, implementing application architecture for developer productivity, and driving a high reliability culture in a ~200 people engineering org.


## Experience

### Colorado State University (2021-Present)

Doing my Math PhD with Professor James B. Wilson on studying the algebraic invariants of tensors. 
During my PhD, I also explored formalized computation in Lean, Computational Group Theory, and Type Theory. My dissertation work is explained in my preliminary exam presentation available at slides.com/chrisliu/prelim.


### Coursera (2015-2021)
<br/>
*At Coursera I had three distinct chapters:*

__(2019-2021) Ending as the first internally promoted Senior Staff Software Engineer__ (I was in the Growth and Infrastructure teams.)

- Served in Site Reliability Engineering. Advanced reliability culture through tools, frameworks, and education. 
Results include sending weekly call-graph reports to the organization to understand API fanout. Introduced flame-graph profiling of services as standard practice. Benchmarked and evangelized threading vs async tradeoffs. Led to a shift away from asynchronous by default for handling all backend services.
- Founding member of application architecture group. Defined the group's charter, roadmap, interfaces, and priorities. Decisions in the group were informed by organizational needs, industry trends, and existing tooling. An example of a decision we made was to have a monorepo of service definitions in Protobuf.
- Implemented application architecture on top of Spring Framework and Coursera's existing infrastructure. This includes service discovery (Envoy), deployment tooling (AWS EC2/ECS), internal service gateway, and internal data schema technology. This allowed the new Java platform to be a first-class citizen within the Coursera technology stack.
- Founding member and leader of technical architecture group. Guided and documented key technical decisions, including making Java the next main backend language at Coursera.

<br/>
__(2017-2019) Ending as a Staff Software Engineer__ (I was in the Growth engineering team)

- Redesigned Coursera catalog search infrastructure from Solr to Algolia. Improved performance (10x speedup), reliability, reduced operational overhead, and made ranking explainable to product and marketing stakeholders. 
More details at [https://medium.com/p/6658617cc330](https://medium.com/p/6658617cc330).
- Expanded in-course intervention systems to enable experimentation, personalization, and out of course targeting. More details at [https://medium.com/p/84cf9b38cd52](https://medium.com/p/84cf9b38cd52).
- Built a recommendation modules framework for consistent display, updates, and iteration across product surfaces.
- Drove growth org investment in web performance. This was done by understanding the Server Side Rendering (SSR) architecture and frontend toolchain at Coursera, alongside executing a Webpack v3 to v4 upgrade. 
More details at [https://medium.com/p/cdfeb817faf8](https://medium.com/p/cdfeb817faf8).

<br/>
__(2015-2017) Ending as a Senior Software Engineer__ (I was on the Analytics team as a Data Infrastructure engineer)

- Built internal data platform as a React/Webpack web app, using Scala/Play services to expose data warehouse for company-wide consumption.
- Developed experimentation framework. This required integrating tracking, statistical hypothesis testing, and reporting infrastructure. Results include consistent tracking across web, iOS, and Android.
- Created the first business definitions at Coursera using BI and rollup tables. Integrated data warehouse with BI tools such as Looker and Tableau.
- Maintained data pipelines on top of AWS DataPipeline using Dataduct, a tool my team open sourced and maintained.


<!-- ### Hulu (2014 Intern)
// - Researched and implemented a real time ingestion and querying pipeline using Druid, an open source distributed column oriented data store, handling up to 30k messages/second. 
-->

## Education

(Expected) (2021-2026) Colorado State University - Doctor of Philosophy (PhD) in Mathematics

(2011-2014) Cornell University - Bachelor of Science (BS) in Computer Science

## Skills

**Languages:** Java, JavaScript, TypeScript, Scala, Python, SQL, Julia, MATLAB, OCaml, Bash, HTML, CSS, YAML, Markdown 

**Platform:** AWS, REST, gRPC, experimentation & AB testing, various Java and Scala frameworks (Spring, Play, etc), various frontend frameworks (React, Backbone, Angular, KnockoutJS), various databases (Cassandra, DynamoDB, Redis, MySQL, PostgreSQL), GraphQL

**Data:** Columnar databases like AWS Redshift, streaming tooling like Kafka, SaaS tooling like Google BigQuery and AWS Athena, Looker, Tableau, ETL pipelines, Airflow, various distributed queues like SQS

**Web:** React, Redux and various other state management tooling, Server Side Rendering, Webpack


<!-- ### Footer

Last updated: May 2013 -->


