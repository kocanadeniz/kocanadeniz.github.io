---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}
<h3>Publications</h3>
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Publication"%}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}</ol>

<h3>Patents</h3>
<ol>{% for post in site.publications reversed %}
  {% if post.type == "Patent"%}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}</ol>
