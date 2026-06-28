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

Useful links
======

- [Resume](/files/My_resume_2026_Jan.pdf)
- [GitHub](https://github.com/Oztobuzz)
- [Kaggle](https://www.kaggle.com/oanhtran1123)
- [Hugging Face](https://huggingface.co/mdjsfhkjashdf)
- [arXiv author search](https://arxiv.org/search/cs?searchtype=author&query=Tran,+O.+N.)
- [Email](mailto:oanh.tranotsc1123@hcmut.edu.vn)

News
======

- **June 2026:** Our paper, "Look Before You Zoom: Adaptive Routing for the Resolution-Context Trade-off in Visual RAG," was accepted at the ICML 2026 Workshop on Efficient Multimodal Question Answering.
- **January 2026:** Updated resume and personal website.

Publications
======

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
