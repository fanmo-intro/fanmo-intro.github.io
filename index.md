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
---

<style>
.lang-tabs {
  display: flex;
  gap: 10px;
  margin-bottom: 1rem;
}
.lang-tabs button {
  padding: 6px 12px;
  border: 1px solid #ddd;
  background: #fff;
  cursor: pointer;
  border-radius: 6px;
  font-weight: 600;
}
.lang-tabs button.active {
  border-color: #2563eb;
  color: #2563eb;
  background: #eef2ff;
}

.lang-pane { display: none; }
.lang-pane.active { display: block; }
</style>

<div class="lang-tabs">
  <button id="btn-en" class="active">EN</button>
  <button id="btn-zh">中文</button>
</div>

<div id="content-en" class="lang-pane active">

<p>
I am currently a full professor at the University of Electronics and Science Technology,
a Researcher at the University of Oxford, where I lead the AI and Graph Learning Group,
and a Visiting Fellow at the
<a href="https://www.cst.cam.ac.uk/" target="_blank">
Department of Computer Science and Technology, University of Cambridge
</a>,
working closely with
<a href="https://www.cl.cam.ac.uk/~pl219/" target="_blank">
Professor Pietro Liò (MAE, FAAIA)
</a>.
My research spans knowledge graphs, graph neural networks, robotics, and machine learning,
with applications in intelligent manufacturing, computational biology, and sustainable systems.
</p>

<p>
Previously, I was a Marie Skłodowska-Curie Fellow at the
Centre for Human-Inspired Artificial Intelligence, University of Cambridge.
I hold a joint Ph.D. from the University of Nottingham,
the University of Oxford, and KTH Royal Institute of Technology,
supported by the EU Horizon 2020 programme.
Over the past few years, I have led and contributed to multi-million-pound research projects,
developed AI-driven systems with partners such as Siemens and ABB,
and published more than 40 papers in top-tier journals and conferences.
</p>

<p>
Beyond research, I serve as Chair of the China Chapter of the
Marie Curie Alumni Association, organizing international forums and academic events.
I am passionate about bridging academia and industry, fostering open collaboration,
and advancing AI for real-world impact.
</p>

<p>
I am always open to collaboration with motivated <strong>students</strong> and
<strong>researchers</strong>.
Feel free to reach out if our interests align.
Please write to
<a href="mailto:fm651@cam.ac.uk">fm651@cam.ac.uk</a>.
</p>

<div id="content-zh" class="lang-pane">
  <p>
    我目前是<strong>电子科技大学教授</strong>，同时担任<strong>牛津大学研究员</strong>，
    并作为<strong>访问学者</strong>在
    <a href="https://www.cst.cam.ac.uk/" target="_blank">
      剑桥大学计算机科学与技术系
    </a>
    开展研究工作，与
    <a href="https://www.cl.cam.ac.uk/~pl219/" target="_blank">
      Pietro Liò 教授（MAE, FAAIA）
    </a>密切合作。
  </p>

  <p>
    欢迎<strong>学生</strong>和<strong>研究人员</strong>与我联系，  
    邮箱：
    <a href="mailto:fm651@cam.ac.uk">fm651@cam.ac.uk</a>
  </p>
</div>


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

<script>
document.addEventListener("DOMContentLoaded", function () {
  const btnEn = document.getElementById("btn-en");
  const btnZh = document.getElementById("btn-zh");
  const en = document.getElementById("content-en");
  const zh = document.getElementById("content-zh");

  btnEn.onclick = () => {
    btnEn.classList.add("active");
    btnZh.classList.remove("active");
    en.classList.add("active");
    zh.classList.remove("active");
  };

  btnZh.onclick = () => {
    btnZh.classList.add("active");
    btnEn.classList.remove("active");
    zh.classList.add("active");
    en.classList.remove("active");
  };
});
</script>
