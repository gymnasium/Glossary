---
layout: gym-default
title: Aquent Gymnasium | Glossary
meta_description: A glossary of terms related to design and development.
---

<header class="main-header">
  <h1>Glossary of Terms</h1>
</header>

<dl class="glossary">
{% assign sorted_terms = site.data.glossary | sort: 'term' %}
{% for term in sorted_terms %}
    <dt>{{ term.term }}</dt>
    <dd>{{ term.def }}</dd>
{% endfor %}
</dl>
