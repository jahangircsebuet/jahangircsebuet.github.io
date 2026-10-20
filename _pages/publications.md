---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

See also my [Google Scholar profile](https://scholar.google.com/citations?user=v7hMP8kAAAAJ&hl=en) and [ORCID record](https://orcid.org/0009-0005-8731-7354).

{% include base_path %}

{% assign pubs = site.publications | sort: 'date' | reverse %}
{% assign current_year = '' %}
{% for pub in pubs %}{% assign pub_year = pub.date | date: "%Y" %}{% if pub_year != current_year %}{% unless forloop.first %}</div>{% endunless %}<h2 id="year-{{ pub_year }}">{{ pub_year }}</h2><div class="pub-list">{% assign current_year = pub_year %}{% endif %}
  <div class="pub">
    <a class="pub__title" href="{% if pub.paperurl and pub.paperurl != '' %}{{ pub.paperurl }}{% else %}{{ base_path }}{{ pub.url }}{% endif %}">{{ pub.title }}</a>
    <p class="pub__excerpt">{{ pub.excerpt | markdownify | strip_html | strip_newlines }}</p>
    <p class="pub__meta">{% if pub.venue and pub.venue != '' %}<span class="pub__venue">{{ pub.venue }}</span> &middot; {% endif %}{{ pub.date | date: "%Y" }} &middot; <a href="{{ base_path }}{{ pub.url }}">details</a></p>
  </div>
{% endfor %}
</div>
