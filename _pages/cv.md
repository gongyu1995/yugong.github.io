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
* Ph.D in Electrical and Computer Engineering, Rutgers University, 2025 (expected)
* M.S. in Information and Communication Engineering, Shanghai Jiao Tong University, 2020
* B.S. in Elctrionic and Information Engineering, Wuhan University of Technology, 2017

Work experience
======
* **Samsung Semiconductor**, San Jose, United States  
  **Intern, System Hardware Engineer** (May 2024 – August 2024)
  * Analyzed the bottleneck of LLM inference on a single GPU system.
  * Optimized dataflow for a GPU-CPU system using an offloading strategy.
  * Designed a CXL-based storage system for LLM inference.

* **ScaleFlux Inc.**, Milpitas, United States  
  **Intern, Hardware Engineering** (May 2022 – August 2022)
  * Designed and validated RSA IP and chip-level micro-architectures.
  * Developed RTL, performed synthesis, linting, and CDC checks.
  * Authored detailed micro-architecture and design documents.
  * Collaborated with architecture designers to troubleshoot, debug, and optimize system performance.

* **Tsinghua University and Shanghai Qizhi Institute**, Shanghai, China  
  **Research Assistant** (September 2020 – July 2021)
  * Investigated quantization techniques for CNN models.
  * Proposed a heterogeneous accelerator utilizing various resources on FPGA.
  * Explored the design space using Reinforcement Learning techniques.
  
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
