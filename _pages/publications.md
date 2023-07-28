---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<!-- # Publications -->
<br>
You can also find my articles on <a href="https://scholar.google.com/citations?user=MOFyr2MAAAAJ">my Google Scholar profile</a>.

  {% for post in site.publications reversed %}
    {% if post.path contains '/pubs/' %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}

<br>

# Manuscripts

  {% for post in site.publications reversed %}
    {% if post.path contains '/manus/' %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
  
  


