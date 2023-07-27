---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<!-- # Publications -->

You can also find my articles on <a href="https://scholar.google.com/citations?user=MOFyr2MAAAAJ">my Google Scholar profile</a>.

  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
 
---
# Manuscripts

  {% for post in site.manuscripts reversed %}
    {% include archive-single.html %}
  {% endfor %}
  
  


