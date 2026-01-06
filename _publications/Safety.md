---
layout: pub
type: article
key: medaisafe25
title: >
  How to Make Medical AI Systems Safer? Simulating Vulnerabilities and Threats in Multimodal Medical RAG Systems
author: Zuo, Kaiwen and Liu, Zelin and Dutt, Raman and Wang, Ziyang and Sun, Zhongtian and Mo, Fan and Lió, Pietro
correspondence: Lió, Pietro and Mo, Fan
abbr: ICASSP-26(Under review)
journal: arXiv preprint
arxiv: 2508.17215
preprint: true
year: 2025
selected: true
code:
abstract: >
  Large Vision–Language Models (LVLMs) augmented with Retrieval-Augmented Generation (RAG) are increasingly deployed in medical AI applications to improve factual grounding by leveraging external clinical image–text retrieval. However, this reliance substantially expands the attack surface. To investigate this risk, we introduce MedThreatRAG, a comprehensive multimodal poisoning framework that systematically simulates vulnerabilities and threat pathways in medical RAG systems by injecting adversarial image–text pairs.
  
  Central to our framework is Cross-Modal Conflict Injection (CMCI), a novel adversarial strategy that embeds subtle yet harmful semantic contradictions between medical images and their associated reports. These contradictions degrade cross-modal alignment, disrupt retrieval, and mislead downstream reasoning—while remaining realistic enough to bypass standard filtering defenses.  

  Experiments on IU-Xray and MIMIC-CXR QA benchmarks show that MedThreatRAG can reduce answer F1 scores by up to 27.66%, and lower LLaVA-Med-1.5 performance to 51.36%, highlighting severe security risks in existing medical RAG pipelines. We further provide concrete design guidelines for building safer multimodal medical AI systems.
bibtex: >
  @article{zuo2025medthreatrag,
    title={How to Make Medical AI Systems Safer? Simulating Vulnerabilities and Threats in Multimodal Medical RAG Systems},
    author={Zuo, Kaiwen and Liu, Zelin and Dutt, Raman and Wang, Ziyang and Sun, Zhongtian and Wang, Yeming and Mo, Fan and Lio, Pietro},
    journal={arXiv preprint arXiv:2508.17215},
    year={2025}
  }
---
