---
permalink: /
title: "Dr. Fan Mo"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

<style>
/* ===== Language tabs ===== */
.lang-tabs {
  display:flex; gap:8px; align-items:center; margin:0 0 1rem 0;
}
.lang-tabs button {
  border:1px solid var(--line,#e5e7eb);
  background:#fff; padding:.45rem .8rem;
  border-radius:8px; cursor:pointer; font-weight:600;
  transition:all .2s ease;
}
.lang-tabs button[aria-selected="true"]{
  border-color:var(--accent,#2563eb);
  color:var(--accent,#2563eb);
  box-shadow:0 4px 10px rgba(37,99,235,.12);
  background:rgba(37,99,235,.05);
}

/* ===== Content panel ===== */
.lang-pane {
  display:none;
  background:#fafafa;
  border-radius:14px;
  padding:1.2rem 1.5rem;
  box-shadow:0 6px 20px rgba(0,0,0,.05);
  line-height:1.75;
}
.lang-pane[aria-hidden="false"] { display:block; animation:fade .4s ease; }
@keyframes fade { from{opacity:0;} to{opacity:1;} }

.lang-pane strong { color:var(--accent,#2563eb); }
</style>

<!-- Language Switcher -->
<div class="lang-tabs" role="tablist" aria-label="Language switcher">
  <button role="tab" id="tab-en" aria-controls="pane-en" aria-selected="true" data-lang="en">EN</button>
  <button role="tab" id="tab-zh" aria-controls="pane-zh" aria-selected="false" data-lang="zh">中文</button>
</div>

<!-- English version -->
<div id="pane-en" class="lang-pane" role="tabpanel" aria-labelledby="tab-en" aria-hidden="false">
  <p><strong>Postdoctoral Researcher</strong> at the <strong>University of Oxford</strong>, where I lead the <strong>AI and Graph Learning Group</strong> and serve as a <strong>Visiting Fellow</strong> at the <strong>Department of Computer Science, University of Cambridge</strong>.  
  My research spans <strong>knowledge graphs, graph neural networks, robotics, and machine learning</strong>, with applications in <strong>intelligent manufacturing, computational biology, and sustainable systems</strong>.</p>

  <p>Previously, I was a <strong>Marie Skłodowska-Curie Fellow</strong> at the <strong>Centre for Human-Inspired Artificial Intelligence, University of Cambridge</strong>.  
  I hold a joint Ph.D. from the <strong>University of Nottingham</strong>, the <strong>University of Oxford</strong>, and <strong>KTH Royal Institute of Technology</strong>, supported by the <strong>EU Horizon 2020</strong> programme.  
  Over the past few years, I have led and contributed to multi-million-pound research projects, developed AI-driven systems with partners such as <strong>Siemens</strong> and <strong>ABB</strong>, and published more than <strong>40 papers</strong> in top-tier journals and conferences.</p>

  <p>Beyond research, I serve as <strong>Chair of the China Chapter of the Marie Curie Alumni Association</strong>, organizing international forums and academic events.  
  I am passionate about <strong>bridging academia and industry</strong>, fostering <strong>open collaboration</strong>, and advancing <strong>AI for real-world impact</strong>.  
  You can find me on <a href="https://scholar.google.com/citations?user=XXXX" target="_blank" rel="noopener" style="color:#d6336c; font-weight:600;">Google Scholar</a>, <a href="mailto:you@example.com" style="color:#d6336c; font-weight:600;">Email</a>, and <a href="https://github.com/yourname" target="_blank" rel="noopener" style="color:#d6336c; font-weight:600;">GitHub.
</a>.
.</p>
</div>



<!-- Chinese version -->
<div id="pane-zh" class="lang-pane" role="tabpanel" aria-labelledby="tab-zh" aria-hidden="true">
  <p>我现为剑桥大学<strong>“人工智能研究中心”</strong>的<strong>玛丽·居里学者</strong>，并隶属于剑桥<strong>三一学院</strong>从事博士后研究工作。  
  我的研究聚焦于<strong>知识图谱、图神经网络、机器人技术与机器学习</strong>，致力于推动其在<strong>智能制造、计算生物学与可持续系统</strong>等领域的应用。</p>

  <p>我拥有<strong>诺丁汉大学、牛津大学与瑞典皇家理工学院</strong>联合授予的博士学位，期间获得<strong>欧盟地平线 2020 项目</strong>资助。  
  近年来，我主持和参与多个总额达数百万英镑的国际科研项目，与<strong>西门子、ABB</strong>等企业联合开发 AI 系统，发表学术论文<strong>40 余篇</strong>，其中多篇发表于国际顶级期刊与会议。</p>

  <p>除科研工作外，我还担任<strong>“玛丽·居里学者协会中国分会”主席</strong>，积极组织国际论坛与学术活动。  
  我热衷于推动<strong>产学研融合</strong>、促进<strong>中欧科研交流</strong>，并致力于将人工智能应用于<strong>实际问题解决</strong>之中。</p>
</div>

<script>
(function(){
  const tabs=document.querySelectorAll('.lang-tabs [role="tab"]');
  const panes=document.querySelectorAll('.lang-pane');
  function setLang(lang){
    tabs.forEach(b=>b.setAttribute('aria-selected',b.dataset.lang===lang));
    panes.forEach(p=>p.setAttribute('aria-hidden',p.id!=='pane-'+lang));
  }
  tabs.forEach(b=>b.addEventListener('click',()=>setLang(b.dataset.lang)));
})();
</script>


---


# Research Interests

- **Knowledge Graphs & Graph Neural Networks**: semantic modeling, embedding, reasoning for manufacturing and biomedical applications  
- **Machine Learning & AI Systems**: reinforcement learning (DQN, DDQN, DDPG), multimodal fusion, interpretable AI  
- **Computer Vision**: object detection, human–robot interaction, defect inspection, 3D reconstruction  
- **Natural Language Processing**: large language models, information extraction, semantic alignment with knowledge graphs  
- **Robotics & Digital Twins**: motion planning, multi-agent control, AI-driven digital twins for adaptive manufacturing  
- **Computational Sustainability & Biology**: AI for life cycle assessment, traceability, and systems biology  

---


# Services

### Editorial Roles
- Editorial Board Member, *International Journal of Manufacturing Research*
- Guest Editor, *Applied Science*, Topic: Trends and Prospects in Advanced Automated Manufacturing Systems
- Associate Editor, *Journal of Automation and Intelligence*
- Young Editorial Board Member, *Journal of Complex Engineering Systems*  

### Conference Service
- Session Chair, *FAIM* (2022–2024)  
- Session Chair, *22nd IFAC World Congress* (2023)  
- Session Chair, *ACM MUM* (2024)  
- Lead Organizer & Chair, *MCAA China Chapter Annual Conferences & Forums* (2023–2024)  
- Organizer, *MCAA Asia Connect Forum on AI and Computer Science* (2024)  

### Reviewer
- *IEEE Transactions on Industrial Informatics*  
- *Journal of Intelligent Manufacturing*  
- *Engineering Applications of Artificial Intelligence*  
- *Expert Systems with Applications*  
- *Journal of Manufacturing Systems*  
- Reviewer for *NeurIPS* and other AI/manufacturing conferences  

---
# News  

- **Jun. 2025** – Paper *“Intelligent Configuration Management in Modular Production Systems: Integrating Operational Semantics with Knowledge Graphs”* published in *Journal of Manufacturing Systems*  
- **May. 2025** – Paper *“LLM-MANUF: An Integrated Framework of Fine-Tuning Large Language Models for Intelligent Decision-Making in Manufacturing”* published in *Advanced Engineering Informatics*  
- **May. 2025** – Paper *“Omni-Scale Spatio-Temporal Attention Network for Impact Localization of Sandwich Composite Panels”* published in *Engineering Applications of Artificial Intelligence*  
- **Apr. 2024** – Paper *“Semantic Models and Knowledge Graphs as Manufacturing System Reconfiguration Enablers”* published in *Robotics and Computer-Integrated Manufacturing*  
- **Mar. 2024** – Invited talk *“Advancing Capability Matching in Manufacturing Reconfiguration with LLMs”* at *FAIM 2024*  
- **Jul. 2024** – Paper *“Advancing Capability Matching in Manufacturing Reconfiguration with Large Language Models”* published in *FAIM 2024 Proceedings*  
- **Sep. 2024** – Paper *“Instructional Design and Disability”* presented at *HELMeTO 2024*  
- **Dec. 2023** – Paper *“PLC Orchestration Automation to Enhance Human-Machine Integration in Adaptive Manufacturing Systems”* published in *Journal of Manufacturing Systems*  
- **Nov. 2023** – Paper *“A Modular Artificial Intelligence and Asset Administration Shell to Streamline Testing Processes in Manufacturing Services”* published in *Journal of Manufacturing Systems*  
- **Nov. 2023** – Paper *“Agent-Based Manufacturing – Review and Expert Evaluation”* published in *International Journal of Advanced Manufacturing Technology*  
- **Nov. 2023** – Paper *“Big Data Life Cycle in Shop-Floor – Trends and Challenges”* published in *IEEE Access*  
- **Nov. 2023** – Paper *“Variational Bayesian Learning with Reliable Likelihood Approximation for Accurate Process Quality Evaluation”* published in *IEEE Transactions on Industrial Informatics*  
- **Nov. 2023** – Paper *“Investigating Multi-level Ontology to Support Manufacturing during Demand Fluctuation”* published in *LoDiSA 2023*  
- **Oct. 2023** – Paper *“GRA-Net: Global Receptive Attention Network for Surface Defect Detection”* published in *Knowledge-Based Systems*  
- **Oct. 2023** – Paper *“A Multi-phase Scheduling Method for Reconfigurable Flexible Job-shops with Multi-machine Cooperation based on a Scout and Mutation-based Aquila Optimiser”* published in *CIRP Journal of Manufacturing Science and Technology*  
- **Oct. 2023** – Paper *“Automatic Detection of Wire Bonding Defects in Microwave Components using Multi-Stage Hybrid Methods Based on Deep Learning”* published in *Measurement Science and Technology*  
- **Oct. 2023** – Paper *“Integration of Cutting-Edge Interoperability Approaches in Cyber-Physical Production Systems and Industry 4.0”* published in *Design, Applications, and Maintenance of Cyber-Physical Systems*  
- **Sep. 2023** – Paper *“Cloud Based Decision Making for Multi-Agent Production Systems”* published in *EPIA Conference on Artificial Intelligence (LNAI)*  
- **Sep. 2023** – Paper *“Capacity Modeling and Measurement for Smart Elastic Manufacturing Systems”* presented at *SAE AeroTech Conference*  
- **Sept. 2023** – Session Chair, *34th FAIM Conference*  
- **Aug. 2023** – Paper *“A Framework for Manufacturing System Reconfiguration and Optimisation Utilising Digital Twins and Modular Artificial Intelligence”* published in *Robotics and Computer-Integrated Manufacturing*  
- **Jul. 2023** – Paper *“Enabling Coordinated Elastic Responses of Manufacturing Systems through Semantic Modelling”* published in *IFAC World Congress*  
- **Jul. 2023** – Session Chair, *22nd IFAC World Congress*  
- **Apr. 2023** – Paper *“A Maturity Model for the Autonomy of Manufacturing Systems”* published in *International Journal of Advanced Manufacturing Technology*  
- **Nov. 2022** – Paper *“A Coupling Optimisation Method of Production Scheduling and Computation Offloading for Intelligent Workshops with Cloud-Edge-terminal Architecture”* published in *Journal of Manufacturing Systems*  
- **Oct. 2022** – Paper *“A Global Interactive Attention-based Lightweight Denoising Network for Locating Internal Defects of CFRP Laminates”* published in *Engineering Applications of Artificial Intelligence*  
- **Aug. 2022** – Paper *“A Framework for Manufacturing System Reconfiguration Based on Artificial Intelligence and Digital Twin”* published in *FAIM 2022 Proceedings*  
- **Aug. 2022** – Delivered Marie Curie Fellowship workshop with 500+ attendees  
- **Jun. 2022** – Paper *“Service Based Approach to Asset Administration Shell for Controlling Testing Processes in Manufacturing”* published in *MIM 2022 Proceedings (IFAC)*  


---
