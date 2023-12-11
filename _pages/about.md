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
{% include_relative includes/intro.md %}

<span class='anchor' id='-news'></span>
{% include_relative includes/news.md %}

<span class='anchor' id='-publications'></span>
{% include_relative includes/pub.md %}

<span class='anchor' id='-educations'></span>
{% include_relative includes/educations.md %}

<span class='anchor' id='-honors-and-awards'></span>
{% include_relative includes/honers.md %}

<span class='anchor' id='-internships'></span>
{% include_relative includes/internships.md %}
