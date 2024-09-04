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
* **Programming Languages:**
  * Python, C, Verilog/System Verilog, Linux Shell, Matlab
* **Tools & Platforms:**
  * PyTorch, Quartus, Vivado, DS

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
* Reviewer:
  * NIPS, ICML, ICLR, AAAI, ICCAD, TCAD, Asilomar, ISVLSI

Honors and Awards
=====
* 2023  **6-th Place Winner** of 2023 ACM/IEEE TinyML Design Contest
* 2023  ISCA travel grant
* 2023  **Best Paper Runner-up** of AAAI 2023 workshop: DL-Hardware Co-Design for AI Accleration
* 2018  **2-nd Prize** of National Graduate Methematical Modeling Competition of China
