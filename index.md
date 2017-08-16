---
layout: gym-default
title: Aquent Gymnasium | Glossary
---

<header class="main-header">
  <h1>Glossary of Terms</h1>
</header>

<dl class="glossary">
{% for term in site.data.glossary %}
    <dt>{{ term.term }}</dt>
    <dd>{{ term.def }}</dd>
{% endfor %}
</dl>
