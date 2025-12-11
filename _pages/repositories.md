---
layout: page
permalink: /repositories/
title: repositories
description: Publication code and other related projects.
nav: true
nav_order: 4
---
<style>
/* Override page layout constraints for repositories */
.post-content,
article,
.page-content {
  max-width: 100% !important;
}
</style>
{% if site.data.repositories.github_repos %}
<div class="repositories">
     {% for repo in site.data.repositories.github_repos %}
       {% include repository/repo.liquid repository=repo %}
     {% endfor %}
</div>
{% endif %}
