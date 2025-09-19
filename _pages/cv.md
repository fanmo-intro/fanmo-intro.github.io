---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV (PDF)](/files/CV_Fan_Mo.pdf)

Education
======
* **Ph.D., AI, Knowledge Graphs & Robotics**, Joint PhD (University of Nottingham · University of Oxford · KTH), 2020–2023  
* **M.Sc., Software Engineering**, University of Oxford, 2022–2024  
* **M.Sc., Engineering**, University of Stuttgart, 2015–2017  
* **B.Eng., Control/Automation**, Tongji University (visiting at TUM), 2009–2013

Work experience
======
* **Postdoctoral Researcher**, University of Cambridge — 2024–present  
  * AI for environmental sustainability; knowledge graphs & LLMs for LCA transparency; multimodal analytics.
* **Team Lead (AI) & Postdoctoral Researcher**, University of Oxford — 2025–present  
  * 3D human pose estimation (RGB/Depth/Thermal/mmWave/LiDAR), graph learning, RNA–drug discovery.
* **Research Fellow**, University of Nottingham — 2020–2024  
  * Modular/reconfigurable manufacturing, digital twins, RL+GNN for scheduling and capability matching.
* **Visiting Researcher**, ETH Zürich (CVG) — 2022–2023  
* **Software Engineer**, Volkswagen Group — 2017–2020  
  * Predictive maintenance, anomaly detection, connected/automated systems.

Selected skills
======
* **Graph Learning & KGs**: GNNs (heterogeneous graphs), Neo4j, reasoning/integration  
* **Reinforcement Learning**: DQN/DDQN/DDPG, policy evaluation, PyTorch/Tianshou/RLlib  
* **Multimodal Perception**: RGB/Depth/Thermal/mmWave/LiDAR fusion; 3D pose/mesh  
* **Robotics**: embodied AI, task & motion planning, KUKA/ABB/FANUC; PLC orchestration  
* **Software**: Python, PyTorch, PyG, NumPy/Pandas, Docker, Git; Brightway2, ecoinvent

Honors & awards
======
* Marie Skłodowska-Curie Actions (MSCA) scholar  
* DAAD Artificial Intelligence & Robotics Fellowship  
* **Outstanding Doctoral Dissertation**, Shanghai Jiao Tong University  
* National Scholarship for Doctoral Students (twice)

Service and leadership
======
* **Vice Chair**, MCAA China Chapter (800+ members; best chapter award)  
* **Associate Editor / PC**: RAL, ICRA 2024/2025, IROS 2024  
* Organizer/Speaker: international workshops on AI, robotics, sustainability

Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Talks
======
<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

Teaching
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
