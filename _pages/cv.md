---
layout: archive
title: "Bio"
permalink: /bio/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Before starting at Oxford, I completed my B.Sc. in Computer Science and Mathematics at the [University of Edinburgh](https://www.ed.ac.uk/), graduating with First Class Honours and ranking first in my cohort. Followed by an M.Sc. in Artificial Intelligence and Machine Learning at [Imperial College London](https://www.imperial.ac.uk/), graduating with distinction. Here I worked as a Research Assistant in the [Brain and Signal Analysis Lab](https://basira-lab.com/) where I developed computationally efficient knowledge distillation methods for graph neural networks. During my studies, I was actively involved in undergraduate teaching and tutoring in machine learning, data science, and foundational computing courses. I have also worked in industry as a Data Scientist in the Applied AI & Machine Learning team at [J.P. Morgan](https://www.jpmorgan.com/insights/technology/artificial-intelligence), where I designed, implemented, and optimized end-to-end machine learning systems deployed in large-scale production environments.

CV
======

A full CV can be found [here](https://lorenzostigliano.github.io/files/cv/Lorenzo_CV_Full.pdf).
I also keep a CV of [failures](https://lorenzostigliano.github.io/files/cv/Lorenzo_CV_Full_Failures.pdf) - because rejection is part of the process.

## Education
* D.Phil. in [Machine Learning (Computational Biology)](https://www.ox.ac.uk/admissions/graduate/courses/healthcare-data-science), University of Oxford, 2029
* M.Sc. in [Artificial Intelligence and Machine Learning](https://www.imperial.ac.uk/study/courses/postgraduate-taught/computing-artificial-intelligence-msc/), Imperial College London, 2023
* B.Sc. in [Computer Science and Mathematics](https://study.ed.ac.uk/programmes/undergraduate/64-computer-science-and-mathematics), University of Edinburgh, 2021

## Experience

<ul>
  <li>
    <div style="display:flex; justify-content:space-between;">
      <strong>J.P. Morgan</strong>
      <span><em>Sep 2023 - Sep 2025</em></span>
    </div>
    <div style="display:flex; justify-content:space-between;">
      <span>Data Scientist</span>
      <span>London, UK</span>
    </div>
    <ul>
      <li>Developed end-to-end machine learning pipelines for time-series signal prediction</li>
    </ul>
  </li>
  <li>
    <div style="display:flex; justify-content:space-between;">
      <strong>Imperial College London</strong>
      <span><em>Apr 2023 - Sep 2023</em></span>
    </div>
    <div style="display:flex; justify-content:space-between;">
      <span>Research Assistant</span>
      <span>London, UK</span>
    </div>
    <ul>
      <li>Developed a novel knowledge distillation method for graph neural networks</li>
    </ul>
  </li>
  <li>
    <div style="display:flex; justify-content:space-between;">
      <strong>J.P. Morgan</strong>
      <span><em>Jun 2022 - Aug 2022</em></span>
    </div>
    <div style="display:flex; justify-content:space-between;">
      <span>Data Scientist Intern</span>
      <span>London, UK</span>
    </div>
    <ul>
      <li>Led data analytics initiatives using large-scale web data to extract insights for over 1M companies</li>
    </ul>
  </li>
  <li>
    <div style="display:flex; justify-content:space-between;">
      <strong>Barclays</strong>
      <span><em>Aug 2021 - Jun 2022</em></span>
    </div>
    <div style="display:flex; justify-content:space-between;">
      <span>Software Engineer</span>
      <span>Glasgow, UK</span>
    </div>
    <ul>
      <li>Developed full-stack web applications to evaluate QA platform release impacts</li>
    </ul>
  </li>
  <li>
    <div style="display:flex; justify-content:space-between;">
      <strong>Barclays</strong>
      <span><em>Jul 2020 - Aug 2020</em></span>
    </div>
    <div style="display:flex; justify-content:space-between;">
      <span>Software Engineering Intern</span>
      <span>Glasgow, UK</span>
    </div>
    <ul>
      <li>Built AWS-based applications to visualize client relationships</li>
    </ul>
  </li>
  <li>
    <div style="display:flex; justify-content:space-between;">
      <strong>University of Edinburgh</strong>
      <span><em>Jun 2020</em></span>
    </div>
    <div style="display:flex; justify-content:space-between;">
      <span>Research Assistant</span>
      <span>Edinburgh, UK</span>
    </div>
    <ul>
      <li>Contributed to the DAPHNE research project</li>
    </ul>
  </li>
  <li>
    <div style="display:flex; justify-content:space-between;">
      <strong>Imagination Technologies</strong>
      <span><em>Jun 2019 - Jul 2019</em></span>
    </div>
    <div style="display:flex; justify-content:space-between;">
      <span>Software Engineering Intern</span>
      <span>Kings Langley, UK</span>
    </div>
    <ul>
      <li>Developed a full-stack application automating hardware emulator workflows</li>
    </ul>
  </li>
</ul>

## Awards

* **Fully Funded Doctoral Studentship EPSRC Centre for Doctoral Training in Healthcare Data Science**  
  Competitive award supporting doctoral training and research in Healthcare Data Science at the University of Oxford.

* **University of Edinburgh Class Prize**  
  Awarded to the top-ranked student for the highest overall academic performance across Computer Science and Mathematics.

* **King’s College Class Prize for Mathematics**  
  Awarded for exceptional academic achievement in mathematics.

* **King’s College Honorary Scholarship**  
  Awarded in recognition of outstanding academic performance at AS Level.

<!-- ## Skills
* Python, Java, SQL, Bash
* PyTorch, PyTorch Geometric, MLflow, LangChain

## Languages
* Spanish (Native), English (Fluent), Italian (Conversational) -->

## Research
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->

## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
