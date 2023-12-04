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

I am a computer science graduate from the [University of Rochester](https://rochester.edu/). I am currently a researcher at the [ROC HCI](https://roc-hci.com/) Lab where I work under the supervision of Professor [Ehsan Hoque](https://hoques.com/). I have previous experience in Cryptography research under Professor [Muthu Venkitasubramaniam](https://muthu.georgetown.domains/). My current research focuses on Multimodal Learning, Medical AI, and building robust & unbiased ML/DL pipelines. I am passionate about accessibility, augmentation, assistive technology, and medical AI research. I am a huge [Al-Ahly]() and [AC-Milan]() fan and I enjoy playing football and Fifa in my free time.

## Work

- Medical AI reseacher @ [ROC HCI](https://roc-hci.com/)

## Research Interests

- Multimodal Learning
  - Co-Learning, Alignment, Fusion.
- Medical AI
  - Early screening, Tracking, and Intervention.
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
