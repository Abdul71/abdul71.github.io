---
layout: default
title: "./Abdelrahman/"
description: "Medical AI researcher"
---

## About Me

<img class="profile-picture" src="images/profile_picture.png" alt="Profile picture" style="width: 20%;">

{% highlight bash %}
$ whoami
Abdelrahman: ml_researcher. engineer. programmer. football_enthusiast.
{% endhighlight %}

I am a Master’s student in Computer Science at the [University of Rochester](https://rochester.edu/). I am currently a graduate ML researcher at the [ROC HCI](https://roc-hci.com/) Lab under the supervision of Professor [Ehsan Hoque](https://hoques.com/). My research focuses on Multimodal Learning, Medical AI, and building robust & unbiased ML/DL pipelines.  I’m passionate about leveraging AI for accessibility, early disease screening, and assistive technologies. I am a huge [Al-Ahly]() and [AC-Milan]() fan and I enjoy playing football and Fifa in my free time.

## Work

- ML reseacher @ [ROC HCI](https://roc-hci.com/)

## Research Interests

- Multimodal Learning
  - Co-Learning, Vision Language Models, Diffusion Models
- Explainable & Trustworthy AI
  - Interpretable Model Decisions, Ethical Frameworks, Bias Mitigation
- Medical AI
  - Early screening, Tracking, and Intervention.
- Assistive Technology
  - Accessibility
 
## Recent Publications

{% assign counter = 0 %}

{% for pub in site.data.publications.journals limit:2 %}

{% assign counter = counter | plus:1 %}

<div class="pub-item">
<div class="pub-title"><span>[{{ counter }}]</span><a href="{{ pub.url }}" target="_blank"><b>{{ pub.title }}</b></a><br></div>
<div><i class="ri-group-line"></i> {{ pub.authors }}</div>
<div><i class="ri-book-3-line"></i>  {{ pub.conference }}</div>
</div>

{% endfor %}


{% for pub in site.data.publications.confs limit:2 %}

{% assign counter = counter | plus:1 %}

<div class="pub-item">
<div class="pub-title"><span>[{{ counter }}]</span><a href="{{ pub.url }}" target="_blank"><b>{{ pub.title }}</b></a><br></div>
<div><i class="ri-group-line"></i> {{ pub.authors }}</div>
<div><i class="ri-book-3-line"></i>  {{ pub.conference }}</div>
</div>

{% endfor %}


<a href="/publications"><i class="ri-add-circle-line"></i> **View More**</a>
