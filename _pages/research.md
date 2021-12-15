---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My research lies at the intersection of genetics and data science. I am interested in human genetic variation: between populations and within populations. I work on both arms of the human genomics experimental design--family-based studies and large population cohorts--to identify trait-associated variation.

I have worked with the Million Veterans Program, the Global Lipids Consortium, the Genotype-Tissue Expression project, and various consortia to identify trait-associated genes and signals. I am currently characterizing gene regulation in the Amish population. 

I'm also interested in re-examining existing genomic datasets for novel discovery. 
<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
