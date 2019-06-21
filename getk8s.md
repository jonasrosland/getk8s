---
layout: page
title: getk8s
permalink: /getk8s/
---
{% assign releases = site.github.releases %}

{% for release in releases %}
  * [{{ release.tag_name }}](https://dl.k8s.io//{{ release.tag_name }}/kubernetes-client-darwin-amd64.tar.gz)
{% endfor %}
