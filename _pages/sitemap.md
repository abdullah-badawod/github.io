---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: false
---

A list of all the posts and pages found on the site. For you robots out there, an [XML version]({{ "sitemap.xml" | relative_url }}) is available for digesting as well.

<h2>Pages</h2>
{% for page in site.pages %}
  <ul>
    <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
  </ul>
{% endfor %}

<h2>Posts</h2>
{% for post in site.posts %}
  <ul>
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  </ul>
{% endfor %}

<h2>Collections</h2>
{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    {% capture label %}{{ collection.label }}{% endcapture %}
    {% if label != written_label %}
      <h3>{{ label }}</h3>
      {% capture written_label %}{{ label }}{% endcapture %}
    {% endif %}
  {% endunless %}
  <ul>
    {% for post in collection.docs %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
