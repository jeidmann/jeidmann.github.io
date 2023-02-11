---
layout: page
permalink: /repositories/
title: repositories
description:
nav: true
nav_order: 3
---

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

<h2>Other Repositories</h2>
<u><b>Click on the dataverse icons to access links to the following repositories. </u></b>
<div class="container">
Code and data associated with the publication titled: <p><i><b> New remote method to systematically extract bedrock channel width of small catchments across large spatial scales using high-resolution digital elevation models </b></i></p>
  <div class="row">
    <div class="col">
        <a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/KY4KO4">{%- include figure.html path="assets/img/publication_preview/HarvardData.png" title="Harvard Dataverse" class="img-fluid rounded z-depth-1"%}</a>    
    </div>
  </div>
</div>

<div class="container">
Data associated with the publication titled: <p><i><b> Channel Response and Reservoir Delta Evolution from Source to Sink Following an Extreme Flood</b></i></p>
  <div class="row">
    <div class="col">
        <a href="https://dataverse.harvard.edu/dataverse/Eidmann-et-al-2021">{%- include figure.html path="assets/img/publication_preview/HarvardData.png" title="Harvard Dataverse" class="img-fluid rounded z-depth-1"%}</a> 
    </div>
  </div>
</div>