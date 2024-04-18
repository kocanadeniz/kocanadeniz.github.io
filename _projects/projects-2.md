---
title: "HearSmart"
excerpt: "EEG-based hearing aid for auditory attention decoding (AAD)<br/><img src='/images/Motivation2.jpg' width='500px' height='300px'>"
collection: projects
layout: archive
author_profile: true
---

HearSmart involves building a brain-computer interfaced hearing aid using EEG to solve the auditory attention decoding problem. The goal of this project is to determine which speaker out of multiple speakers — a cocktail-party scenario — a listener is focusing at based on the EEG signals recorded. I have been helping with the system design, which is still an on-going process, and have worked on model pruning and quantization with spiking neural network algorithms.

<img src='/images/FlowDiagram2.jpg' alt='test'>

<h3>Publications: </h3> 
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Publication"%}
  	{% if post.subject == "cortico" %}
    	{% include archive-single-pub.html %}
    {% endif %}
  {% endif %}
{% endfor %}</ol>

