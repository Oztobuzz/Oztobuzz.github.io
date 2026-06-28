---
permalink: /
title: "Oanh N. Tran"
description: "Oanh N. Tran is a research assistant at VinUniversity working on failure modes, behavioral reliability, evaluation, and mitigation for multimodal AI systems."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
<div class="pronunciation">
  <span class="pronunciation-label">How to say my name:</span>
  <span class="pronunciation-text">Vietnamese: <strong>Oanh Trần</strong>; English-friendly: <strong>Wahn Trun</strong>.</span>
  <button type="button" class="pronunciation-button" data-pronounce-text="Oanh Trần" data-pronounce-lang="vi-VN">Listen Vietnamese</button>
  <button type="button" class="pronunciation-button" data-pronounce-text="Wahn Trun" data-pronounce-lang="en-US">Listen English</button>
</div>

Hello, my name is **Oanh N. Tran** (also **Oanh Tran** or **Tran Ngoc Oanh**). I am a research assistant at **[VinUniversity](https://vinuni.edu.vn/)**, advised by **[Prof. Khoa D. Doan](https://vinuni.edu.vn/people/khoa-d-doan-phd/)**. My research studies failure modes and behavioral reliability in multimodal AI systems, with a focus on understanding why these systems behave unreliably and how to mitigate their failures.


Beyond AI, I enjoy playing **Teamfight Tactics (TFT)** and **Ultimate Disc** 🥏, as well as trying new recipes through **cooking and baking** 🍳🧁—though definitely not washing dishes 🫧.


________

## News

<div class="section-content">
<ul class="news-list">
  <li>
    <span class="news-date">06.2026</span>
    <span class="news-text"><a href="https://arxiv.org/abs/2606.21968">ViRGo</a>, was accepted to the ICML 2026 Workshop on Efficient Multimodal Question Answering.</span>
  </li>
  <li>
    <span class="news-date">11.2024</span>
    <span class="news-text">I graduated from HCMUT with a GPA of 3.6/4.0.</span>
  </li>
  <li>
    <span class="news-date">08.2024</span>
    <span class="news-text">I started working as a Research Assistant at the <a href="https://mail-research.com/"> MAIL Research Group</a>.</span>
  </li>
  <li>
    <span class="news-date">06.2024</span>
    <span class="news-text">Our paper, “Cross-Data Knowledge Graph Construction for LLM-enabled Educational Question-Answering System: A Case Study at HCMUT,” was accepted to AIQAM ’24.</span>
  </li>
</ul>
</div>


______


## Publications

{% include base_path %}

<div class="section-content">
{% include publication-list.html %}
</div>

<script>
  document.querySelectorAll(".pronunciation-button").forEach(function(button) {
    button.addEventListener("click", function() {
      if (!("speechSynthesis" in window)) {
        return;
      }

      var utterance = new SpeechSynthesisUtterance(button.dataset.pronounceText);
      var lang = button.dataset.pronounceLang;
      var voices = window.speechSynthesis.getVoices();
      var matchingVoice = voices.find(function(voice) {
        return voice.lang && voice.lang.toLowerCase().indexOf(lang.toLowerCase()) === 0;
      });

      utterance.lang = lang;
      if (matchingVoice) {
        utterance.voice = matchingVoice;
      }
      window.speechSynthesis.cancel();
      window.speechSynthesis.speak(utterance);
    });
  });
</script>
