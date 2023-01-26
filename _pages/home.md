---
layout: page
permalink: /home/
title: home
---

{% capture my_include %}{% include_relative home_content.md %}{% endcapture %}
{{ my_include | markdownify }}