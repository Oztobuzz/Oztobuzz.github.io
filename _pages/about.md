---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

My name is **Oanh N. Tran**. I am a Computer Science researcher interested in trustworthy AI, multimodal AI, and efficient vision-language systems, especially for large language models and visual question answering.

My recent work studies how models can reason more efficiently over visual evidence, including retrieval-augmented and adaptive routing methods for multimodal question answering.


News
======

- **June 2026:** Our paper, “Look Before You Zoom: Adaptive Routing for the Resolution-Context Trade-off in Visual RAG,” was accepted to the ICML 2026 Workshop on Efficient Multimodal Question Answering.
- **November 2024:** I graduated from HCMUT with a GPA of 3.6/4.0.
- **August 2024:** I started working as a Research Assistant at the MAIL Research Group.
- **June 2024:** Our paper, “Cross-Data Knowledge Graph Construction for LLM-enabled Educational Question-Answering System: A Case Study at HCMUT,” was accepted to AIQAM ’24: Proceedings of the 1st ACM Workshop on AI-Powered Q&A Systems for Multimedia.


Publications
======

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
