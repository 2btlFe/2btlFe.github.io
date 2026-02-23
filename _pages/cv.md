---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
- **M.S. in Artificial Intelligence**, Sungkyunkwan University (SKKU), Mar 2025 – Present  
  Advisor: Prof. Jae-Pil Heo.
- **B.S. in Electronic Electrical Engineering & Computer Science (Double Major)**, SKKU, Mar 2019 – Feb 2025  
  GPA: 4.08/4.5; Honors: SKKU Magna Cum Laude.

## Research Experience
- **Graduate Researcher, SKKU** (Mar 2025 – Present)  
  Open-vocabulary dense prediction, semantic segmentation, and feature upsampling.

## Research Projects
- **Generative AI-based command and control with real-time 3D digital twins** (Jul 2024 – Present)  
  - Supported by IITP under the Ministry of Science and ICT.  
  - Semantic segmentation and 3D reconstruction developer.  
  - Drone imagery 3D reconstruction (COLMAP, 3D Gaussian Splatting) and remote-sensing open-vocabulary segmentation.
- **Detection of AI-based Fake Investigation and Tip Videos** (Oct 2023 – May 2024)  
  - Funded by the Korean National Police Agency & Ministry of Science and ICT ($2.2M total).  
  - Forgery image developer and research data manager.  
  - Deepfake detection, video forgery detection, video inpainting, and video-to-video translation.

## Professional Experience
- **Sergeant, Radar Maintenance — Republic of Korea Air Force** (May 2021 – Feb 2023)  
  Performed radar maintenance and monitoring; conducted routine inspections and troubleshooting.
- **Co-Founder & Developer — Smart Maritime Logistics ICT Mentoring & Startup Audition** (May 2020 – Dec 2020)  
  Built Kalman filter-based GNSS pipelines and Android applications; handled accounting and finance.

## Awards and Honors
- Graduate Excellence Scholarship, 2025 – Present (total: $4,200).
- Academic Scholarship, 2019 – 2025 (total: $2,000).
- SKKU Algorithm Programming Contest, 2023 — Top 10% (prize: $150).

## Skills
- Programming: Python, C/C++.
- Frameworks & Tools: PyTorch, Git, Docker, Slurm.
- Editors & Shell: VSCode, Vim.

## Volunteer Service
- **The Korea Robot Volunteer (non-profit)** (Mar 2016 – Feb 2019)  
  Mentor for line tracing with LEGO Mindstorm; robotics education for local youth and an overseas program in Mongolia.

## Publications
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Talks
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>

## Teaching
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
