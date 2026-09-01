---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

\*: equal contribution

<div class="publication-list">
  {% for publication in site.data.publications %}
    {% unless publication.show == false %}
      {% include publication-item.html publication=publication %}
    {% endunless %}
  {% endfor %}
</div>
