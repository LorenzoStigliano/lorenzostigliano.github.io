---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* D.Phil. (Ph.D.) in Applied Machine Learning, University of Oxford, 2029 (expected)
* M.Sc. in Artificial Intelligence & Machine Learning, Imperial College London, 2023
* B.Sc. in Computer Science and Mathematics, University of Edinburgh, 2021

Work and research experience
======
* Sep 2023 – Sep 2025: Data Scientist (Applied AI & ML)
  * J.P. Morgan Chase & Co., London, UK
  * Developed end-to-end machine learning pipelines for time-series signal prediction using classification models and variational autoencoders
  * Optimized retrieval-augmented generation (RAG) pipelines for large-scale transcript analysis, reducing costs by 70%

* Apr 2023 – Sep 2023: Machine Learning Research Assistant 
  * Imperial College London (Brain and Signal Analysis Lab), London, UK
  * Developed a novel knowledge distillation method for Graph Neural Networks, reducing model parameters by 95% under the supervision of **Prof. Islem Rekik**
  * Achieved 90% reduction in inference time for edge-deployed models while preserving performance

* Jun 2022 – Aug 2022: Data Scientist Intern
  * J.P. Morgan Chase & Co., London, UK
  * Led data analytics initiatives using large-scale web data to extract insights for over +1M companies
  * Optimized ETL pipelines to improve scalability and reduce processing time by 40%

* Aug 2021 – Jun 2022: Software Engineer, 
  * Barclays, Glasgow, UK
  * Developed full-stack web applications to evaluate QA platform release impacts
  * Implemented and optimized queuing systems, reducing background processing runtimes by 50%

* Jul 2020 – Aug 2020: Software Engineering Intern
  * Barclays, Glasgow, UK
  * Built AWS-based applications to visualize client relationships, reducing hosting costs by 90%
  * Designed and integrated RESTful APIs to improve data pipeline scalability and reliability

* Jun 2020: Undergraduate Research Assistant
  * Centre for Speckled Computing, Edinburgh, UK
  * Contributed to the DAPHNE research project as a member of the Centre for Speckled Computing under the supervision of **Prof. Damal Arvind**
  * Investigated potential causal relationships between biomarkers and PM2.5 exposure across multiple test cohorts using statistical hypothesis testing

* Jun 2019 – Jul 2019: Software Engineering Intern
  * Imagination Technologies, Kings Langley, UK
  * Developed a full-stack application automating hardware emulator workflows
  * Implemented RESTful APIs using Flask to ensure scalability and performance

Awards and Prizes
======

TODO: best poster for the thingy

* **University of Edinburgh Class Prize**  
  Awarded to the top-ranked student for the highest overall academic performance across Computer Science and Mathematics.

* **King’s College Class Prize for Mathematics**  
  Awarded for exceptional academic achievement in mathematics.

* **King’s College Honorary Scholarship**  
  Awarded in recognition of outstanding academic performance at AS Level (five A grades).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Python, Java, SQL, Bash
* PyTorch, PyTorch Geometric, MLflow, LangChain