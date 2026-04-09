---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Sc. Computer Science, Concordia University, September 2024 -- April 2026
* B.Sc. Computer Engineering, Isfahan University of Technology, September 2019 -- February 2024 

Experience
======
* Research Assistant, Concordia University, September 2024 -- Present
  * Implemented a browser-based VSR evaluation system using WebRTC with configurable codec parameters and end-to-end network performance instrumentation.
  * Engineered GPU-accelerated inference pipelines using WebGL/WebGPU and Web Workers for parallel execution in real-time streaming scenarios.

* Software Developer, Partak System Vira, February 2022 -- September 2022
  * Built and maintained an enterprise email monitoring dashboard in NestJS serving 1,000+ active users.
  * Engineered a C++ CCTV video server supporting real-time streaming for up to 10 concurrent streams.
  
Skills
======
* Programming: C/C++, Python, JavaScript, Node.js
* AI & ML: PyTorch, TensorFlow.js
* Multimedia & Systems: WebRTC, FFmpeg, WebGPU

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
  
