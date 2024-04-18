---
title: "AREEN - Augmented Reality-based EEG-guided Neglect Detection, Assessment and Rehabilitation system"
excerpt: "My main PhD project - detecting, assessing and rehabilitating visual spatial neglect, a syndrome that occurs by stroke<br/><img src='/images/areen.png' width='500px'>"
collection: projects
layout: archive
author_profile: true
---

AREEN is an electroencephalography (EEG)-based brain-computer interface that incorporates augmented reality to identify the presence of visual spatial neglect (SN) and mapping the estimated neglected visual field. This BCI is used to identify spatiospectral features that best detect participants with SN among stroke survivors. The BCI system was used to collect data from over 25 subjects, and their data are analyzed for neglect detection and field of view estimation. 

<figure class="half" style="display:flex">
    <img style="width:400px" src="/images/detectionResults.png">
    <img style="width:400px" src="/images/estimatedFOV.png">
    <figcaption>A basic diagram showing how AREEN system works (left) and two field of view estimation maps for two subjects (right).</figcaption>
</figure>

<h3>Publications: </h3> 
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Publication"%}
  	{% if post.subject == "neglect" %}
    	{% include archive-single-pub.html %}
    {% endif %}
  {% endif %}
{% endfor %}</ol>

<h3>Patents: </h3> 
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Patent"%}
  	{% if post.subject == "neglect" %}
    	{% include archive-single-pub.html %}
    {% endif %}
  {% endif %}
{% endfor %}</ol>