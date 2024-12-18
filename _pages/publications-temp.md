---
layout: archive
title: "Publications-MD"
permalink: /publications-md/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on my [Google Scholar profile]({{site.author.googlescholar}}).
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category %}
{% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
## {{ category[1].title }}
        {% assign title_shown = true %}
      {% endunless %}
- **{{ post.title }}** {% if post.authors %}by {{ post.authors }}{% endif %}
  {% if post.url %}
    [Read more]({{ post.url }})
  {% endif %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
- **{{ post.title }}** {% if post.authors %}by {{ post.authors }}{% endif %}
  {% if post.url %}
    [Read more]({{ post.url }})
  {% endif %}
  {% endfor %}
{% endif %}