---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/pedigree.png"
---

My research lies at the intersection of genetics and data science. I am interested in human genetic variation: between populations and within populations. How much genetic variation do we see in Indian populations? And how much of this genetic variation has any impact on biology? 

I work on both arms of human genomics experimental design--family-based studies looking at *rare* variation, and large population cohorts that identify *common* trait-associated variation.

I have worked with the Million Veterans Program, the Global Lipids Consortium, the Genotype-Tissue Expression project, and various disease-focused consortia to identify trait-associated genes and signals. I am currently characterizing gene regulation in the Amish population. 

I'm also interested in collaborating with biologists to use bioinformatic approaches to understand questions about gene and genome function. 

### Ongoing work:
 Long-read sequencing in autism-spectrum disorders in Indian populations

 Gene-hunting for Mendelian disorders

 Regulatory mechanisms of human gene classes

### Grants/Funding
* AWS research grant for cloud computing 
* SERB Startup Grant (2021)
* Azim Premji University Startup Grant (2021)
* Gujarat Department of Biotechnology (Co-investigator; Primary Investigator: Dr Harsh Sheth)
* ICMR (Co-investigator; primary investigator: Dr Anshika Srivastava)



<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

  
You can find my full list of publications on my Google Scholar profile.
