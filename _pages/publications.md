---
layout: page
title: Publications
permalink: /Publications/
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<style>
.section-title { padding-bottom: 0.4em; border-bottom: 3px solid #007BFF; margin-bottom: 0.4em; display: block; }
h4 { border-bottom: 1.5px solid #007BFF; padding-bottom: 0.4em; margin-bottom: 0.4em; width: 100%; display: block; }
.publications .row { margin-bottom: 0.8em; }
.publications .author em { font-weight: normal; text-decoration: underline; }
</style>

For a complete list, see <a href="https://scholar.google.com/citations?user=l_nTcokAAAAJ&hl=en">Google Scholar</a>.

<h4>Journal Papers</h4>
<div class="publications">
  {% bibliography --query @article --order descending %}
</div>

<h4>Conference Papers</h4>
<div class="publications">
  {% bibliography --query @inproceedings --order descending %}
</div>
