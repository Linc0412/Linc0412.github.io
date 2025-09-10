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
* Ph.D in Information Systems, University of Melbourne, 12/2027 (expected)
* M.S. in Data Science, University of Southern California, 2020
* B.S. in Management Information Systems, Wuhan University of Technology, 2017

Work experience
======
* 2025: Tutor
  * University of Melbourne
  * Foundations of Information Systems (ISYS10001), Knowledge Management Systems (ISYS90035)

* 11/2020 - 02/2024: Data Scientist
  * China Electronics Technology Group Corporation(CETC)
  * Description: My work involves analyzing large-scale social media data and developing our own early-warning and prediction algorithms to support major         projects. I also take care of project management for the team and handle tasks related to system maintenance and operations.
  * Project 1: Topic Lifecycle Trend Prediction (Facebook Data)  
  I worked on building a prediction algorithm that forecasts how new topics might evolve on Facebook. The model compares new topics with historical ones by       looking at both their lifecycle patterns and text content. Using techniques like K-Shape clustering, DTW, and Jaccard similarity, the system can recommend      the most relevant historical topic trends as references. This approach broke the limitation of “one model per event” in traditional methods and achieved        about 90% accuracy in predicting future trends.
  * Project 2: Topic Popularity Prediction  
  This project focused on predicting whether a new topic would go viral within its early stages of spreading. I designed a comprehensive set of features (e.g.,   user engagement metrics, temporal patterns, and growth dynamics) and applied them to various machine learning models. The outcome provided a practical          approach for offering early warnings of emerging public opinion events and supporting timely decision-making.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service 
======
* Reviewers of International Conference on Information Systems (ICIS, 2025)
* Australasian Conference on Information Systems (ACIS, 2024&2025)

