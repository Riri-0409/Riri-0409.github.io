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

I am a PhD student at the University of New South Wales, supervised by of Dr. Hammond Pearce and Dr. Jason Xue. My research is supported by the UNSW UIPA Scholarship and CSIRO’s Data61 Top-up Scholarship, focusing on vulnerablities of AI models.

My research interest includes AI security and safety, multi-modal models and embodied robotics. I have published several papers at the top international AI and security conferences (e.g. S&P, Usenix, NDSS, WWW) with total <a href='https://scholar.google.com/citations?user=O3skY1PlJqQC'>google scholar citations <strong><span id='total_cit'>80+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=O3skY1PlJqQCJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">S&P 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LACMUS: Latent Concept Masking for General Robustness Enhancement of DNNs]

Shuo Wang, Hongsheng Hu, **Jiamin Chang**, Benjamin Zi Hao Zhao, Minhui Xue
- **S&P 2024**
[**PDF**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=O3skY1PlJqQC&citation_for_view=O3skY1PlJqQC:2osOgNQ5qMEC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The susceptibility of Deep Neural Networks (DNNs) to adversarial attacks and their limited robustness to real-world variations pose substantial challenges to their widespread adoption. Adversarial training has shown promise in fortifying models against such perturbations, however current methods are often specific to a single type of attack and can significantly diminish the model’s overall performance. In response, we present LAtent Concept Masking for robUStness (LACMUS), a novel perceptually-driven methodology that enhances DNN robustness without requiring prior knowledge about the adversarial contexts. We argue that DNNs’ sensitivity to adversarial perturbations and distribution drifts stems from overfitting to non-common concepts within the dataset, leading to an over-reliance on specific learned instances and increased vulnerability. LACMUS addresses this by mapping high-dimensional data into a latent conceptual space to identify and navigate patterns of "non-common concepts" within the latent concept space. 
</div>
</div>


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

  # 🔥 News
# - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
# - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
