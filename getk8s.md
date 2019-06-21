---
layout: page
title: getk8s
permalink: /getk8s/
---
{% assign releases = site.github.releases %}

{% for repository in releases %}
  * [{{ repository.tag_name }}](https://dl.k8s.io//{{ repository.tag_name }}/kubernetes-client-darwin-amd64.tar.gz)
{% endfor %}
