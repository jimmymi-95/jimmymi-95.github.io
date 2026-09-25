---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a multimedia forensics researcher and technologist. My goal as a researcher is to develop trustworthy machine intelligence for understanding, verifying, and protecting visual and auditory information. My work spans several areas of computer science and electrical engineering, including digital media forensics, multimedia security, computer vision, speech and audio processing, machine learning, artificial intelligence, signal processing, and privacy-enhancing technologies. 

As a multimedia security researcher, I believe that technological progress should not only improve our ability to detect manipulated or AI-generated content, but also empower individuals to protect their digital identities before misuse occurs. My research therefore evolves from post-hoc detection toward proactive and preventive defense, with the broader aim of safeguarding people’s facial, vocal, and behavioral identities from unauthorized synthesis, impersonation, and exploitation. 

My research interests lie in trustworthy and secure multimedia intelligence, covering GAN- and diffusion-generated image detection, Deepfake image and video forensics, low-quality and cross-domain manipulation detection, audio Deepfake detection, facial identity protection, voice anonymization, and proactive defense against generative-model misuse. A central theme of my research is to understand the fundamental structures that distinguish authentic multimedia from synthetic content, to characterize how modern generative models reproduce meaningful visual and auditory signals, and to develop stable and generalizable mechanisms for disrupting unauthorized generation. My work is driven by use-inspired basic research: addressing urgent societal challenges in misinformation, fraud, privacy invasion, and identity abuse, while pursuing deeper scientific questions about multimodal authenticity, generative mechanisms, and human-centered protection. I also believe that the future of trustworthy AI depends on making security technologies not only accurate, but also generalizable, interpretable, accessible, and deployable in real-world settings.
