---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<p class="scholar-link">
  <a href="https://scholar.google.com/citations?user={{ site.data.socials.scholar_userid }}" target="_blank" rel="external nofollow noopener">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a>
</p>

<div class="publications">

<h2 class="pub-section">First-author papers</h2>

{% bibliography --group_by none --query @*[category=first-author] %}

<h2 class="pub-section">Leading computational papers</h2>

{% bibliography --group_by none --query @*[category=computational] %}

<h2 class="pub-section">All papers</h2>

{% bibliography %}

</div>
