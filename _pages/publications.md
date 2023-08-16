---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here is a list containing some selected publications. You can find a more comprehensive list of all my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=a2uYCMIAAAAJ&hl=it&oi=ao).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
