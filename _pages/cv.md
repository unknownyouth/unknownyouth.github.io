---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education Background
======
* Master of Science in Computer Science, Duke University, 2027 (expected)

* Bachelor of Engineering in Software Engineering, Dalian University of Technology, 2024
  * **GPA:91**/100 (Rank:**5%**)

Research Experience
======
<!-- **Dynamic LLM-generated Text Benchmark** \| 06/2024 – 11/2024 -->

<div style="display: flex; justify-content: space-between;">
  <strong>Dynamic LLM-generated Text Benchmark</strong>
  <span>06/2024 – 11/2024</span>
</div>

*Independent Research, Supervised by Prof. Dongwon Lee, Pennsylvania State University* 

* Evaluated the deficiency of static benchmark datasets in the face of increasingly powerful LLM and proposed a dynamic LLM-generated text benchmark.
* Utilized the latest or best performing LLM to periodically generate text data, which was used for training and evaluation in the task of AI Authorship Analysis.
* Conducted prompt engineering and comprehensive experiments to clean the generated text data, ensuring the quality and rationality of generation under multilingual scenarios.


<div style="display: flex; justify-content: space-between;">
  <strong>Automated IT Service and Operation Management</strong>
  <span>06/2023 – 11/2023</span>
</div>

*IBM joint development project*

* Implemented intelligent and automated IT services on the ServiceNow platform, improving the visibility of data and the simplicity of manipulation for users
* Captured data changes by using Debezium distributed service and transmitted the configuration information from the database to the ServiceNow platform by leveraging Kafka
* Utilized Docker compose technology for rapid deployment and startup of related data services

<!-- **ZOS/MF System Resources Management with Terraform** \| 07/2022 – 11/2022 -->

<div style="display: flex; justify-content: space-between;">
  <strong>ZOS/MF System Resources Management with Terraform</strong>
  <span>07/2022 – 11/2022</span>
</div>

*IBM joint development project*

* Implemented provider code based on SDK v2 framework and improved the local deployment process of Terraform in different operating system environments
* Designed customized providers to manage the infrastructure resources in Go language, which contributed a lot to creating a lightweight application server on the mainframe
* Realized the batch creation, running and deleting process of WAS Liberty resources using Terraform, resulting in convenience for users to achieve multi-cloud management

Project Experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
