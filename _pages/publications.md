---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my papers on [NASA ADS](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0003-2177-9407&sort=date+desc) or [INSPIRE](https://inspirehep.net/authors/2838294)

Here are my most recent papers:


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
