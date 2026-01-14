---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

![AMLaP 2025, Prague](/images/talks/amlap_talk2.jpg){: .align-center width="85%" }

*AMLaP 2025, Prague – presenting work on bilingual reading and eye movements.*

---

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
