---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
{% include paper-card-style.html %}

You can also find my articles on [Google Scholar]({{ site.author.googlescholar }}).

{% assign papers = site.publications | sort: "date" | reverse %}
{% for post in papers %}
{% include paper-card.html paper=post %}
{% endfor %}
