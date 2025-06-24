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
* B.S. in Computer Science, University of California - Santa Cruz, 2026
* B.S. in Mathematics Theory & Computation, University of California - Santa Cruz, 2026

Work experience
======
* BiomedAI Lab: Research Assistant -- January 2024 - Present
  * Supervisor: Dr. Razvan Marinescu, PhD Candidate Manolis Nikolikakis
  * Collaborated on medical imaging research, focused on 3D brain tissue concentration mapping using MRI data and the NextBrain dataset, supporting modifications to the BMapEst simulation pipeline.
  * Deployed Freesurfer-based image processing tools in Docker containers across a Kubernetes cluster to enable large-scale neuroimaging experiments.
  * Currently contributing to a 3D CT reconstruction pipeline using Gaussian Splatting and computational geometry, with plans to benchmark sparse-view methods for efficient high-fidelity reconstruction.

* Visualization and Interactive Systems Lab (VIS): Research Assistant -- March 2025 - Present
  * Supervisor: Dr. James Davis
  * Contributing to a novel 3D reconstruction pipeline leveraging 3D Gaussian Splatting on ARIA smart glasses video data to recreate human-scale environments for AR navigation and interaction.
  * Designed and implemented an initial pipeline using COLMAP; currently developing a custom alternative to bypass COLMAP preprocessing for significantly faster reconstruction.
  * Benchmarking and integrating sparse-view optimization methods to enhance reconstruction speed and accuracy for real-time AR/VR applications.

* Software Engineering Intern: Summer 2025
  * TBD

* Slugbotics:
  * Autonomous Vehicle Engineer -- October 2022 - June 2023
  * Autonomous Vehicles (Cruz Control) Team Lead -- June 2023 - December 2024

* Autoslug
  * Team Lead (ASL Sign Language Translation) -- June 2023 - Present
  * President -- July 2024 - June 2025

* Course Tutor
  * CSE 12: Intro to Assembly/Digital Logic -- {Spring, Fall} 2023, Spring 2024
  * CSE 101: Data Structures and Algorithms -- Winter 2024
  * CSE 160: Computer Graphics -- {Winter, Spring} 2025
  
* Course Reader
  * CSE 101: Data Structures and Algorithms -- Fall 2024
  * CSE 120: Computer Architecture -- Spring 2025
  * CSE 160: Computer Graphics -- {Winter, Spring} 2025

  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Teaching/
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
   -->
<!--   
Service and leadership
======
* Currently signed in to 43 different slack teams -->
