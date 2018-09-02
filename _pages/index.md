---
layout: splash
permalink: /
header:
  overlay_image: /assets/images/splash.jpg
  overlay_filter: rgba(2, 70, 115, 0.2)
  cta_label: "Our values"
  cta_url: /values/
title: 'Wellness through Movement'
excerpt: 'Every. Body. Welcome.'
feature_row:
  - image_path: /assets/images/pilates.jpg
    alt: "customizable"
    title: "Pilates"
    excerpt: "Mindful movement and thorough method of physical conditioning that delivers profound results."
    url: "/services/pilates/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/essentrics.jpg
    alt: "fully responsive"
    title: "Essentrics"
    excerpt: "A low-impact, dynamic workout that simultaneously lengthens and strengthens every muscle in the body."
    url: "/services/essentrics/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/meditation.jpg
    alt: "100% free"
    title: "Meditation"
    excerpt: "Using the principles of iRest Yoga Nidra, just relax and listen along."
    url: "/services/meditation/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
---

{% include feature_row %}

{% for post in site.posts limit:3 %}
    {% include archive-single.html %}
{% endfor %}
