---
layout: about
title: about
permalink: /

profile:
  align: right
  image: Picture_Fan.jpg

  email: >
    <p>Cambridge Email: fm651<code>[at]</code>cam<code>[dot]</code>ac<code>[dot]</code>uk</p>
    
news: true
selected_papers: true
social: true

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
  You can find me on <a href="https://scholar.google.com/citations?user=oXhA0KkAAAAJ&hl=en" target="_blank" rel="noopener" style="color:#d6336c; font-weight:600;">Google Scholar</a>, <a href="kell6420@ox.ac.uk" style="color:#d6336c; font-weight:600;">Email</a>, and <a href="https://github.com/mf093087" target="_blank" rel="noopener" style="color:#d6336c; font-weight:600;">GitHub</a>.
</p>
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



I am currently pursuing a **Ph.D. in Computer Science** at the [University of Warwick](https://warwick.ac.uk/). In addition to my doctoral studies, I am a **Visiting Researcher** at the [Department of Computer Science and Technology, University of Cambridge](https://www.cst.cam.ac.uk/), working closely with [Professor Pietro Liò(MAE, FAAIA)](https://www.cl.cam.ac.uk/~pl219/). I am also a **Turing Enrichment Student** at the [Alan Turing Institute](https://www.turing.ac.uk/people/doctoral-students/kaiwen-zuo), where I collaborate with [Professor Anthony (Tony) Cohn(FREng, FLSW, CEng, CITP, FAAAI, FEurAI, FAISB, FAAIA, FAIIA, FIET, FBCS)](https://eps.leeds.ac.uk/computing/staff/76/professor-anthony-tony-g-cohn-freng-flsw-ceng-citp). Prior to my Ph.D., I completed an **MSc in Computer Science with Distinction** at [Newcastle University](https://www.ncl.ac.uk/), and earned a **BSc** from [Beijing Jiaotong University](http://en.njtu.edu.cn/).

In addition to my doctoral research, I am the Chief Operating Officer(COO) of **Glacier Wisdom(Tsinghua‑affiliated startup)**, and an active member of **CBAIA**, **UK-CSAE**, and **CLSS-UK**. These affiliations allow me to collaborate with leading researchers across disciplines and foster strong academic networks.

My research interests lie at the intersection of:

- **AI for Healthcare**: Investigating the performance of generalist medical models, and leveraging AGI to empower healthcare.  
- **Safety-oriented AI**: Exploring the safety, trustworthiness, and reliability of general medical models, with a focus on ensuring their robustness and clinical readiness.  
- **Large Language Models (LLMs)**: Examining the diagnostic and prognostic capabilities of large language models in clinical and biomedical contexts.  
- **Agentic Systems**: Advocating for system-level intelligence in next-generation medical AI — to address the complexity of real-world healthcare tasks and support integrated, scalable clinical workflows.  



I am particularly interested in responsible AI systems that align with human values, and in the development of interpretable models for scientific discovery and healthcare reasoning.

I am always open to collaboration with motivated **students** and **researchers**. Feel free to reach out if our interests align!

<div id="news" class="section_break"></div>

## News

{% if page.news %}
  {% include news.html %}
{% endif %}

<div id="publications" class="section_break"></div>

## Selected Publications

{% if page.selected_papers %}
  {% include selected_papers.html %}
{% endif %}

<div id="services" class="section_break"></div>

## Professional Services

- <b>Conference reviewer</b> for AAAI 2024/25, ACL 2024/25, ICLR 2024/25
- <b>Journal reviewer</b> for IEEE Transactions on Computational Social Systems(IEEE TCSS), KSII Transactions on Internet and Information Systems(KSII TIIS)

