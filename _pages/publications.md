---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}
<h3>Journals</h3>
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Journal"%}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}</ol>

<h3>Patents</h3>
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Patent"%}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}</ol>

<h3>Conference Publications</h3>
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Conference"%}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}</ol>

<h3>Other</h3>
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Other"%}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}</ol>