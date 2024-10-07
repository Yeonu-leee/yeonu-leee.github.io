---
layout: default
title: AboutME
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>


<table style="width:100%;">
  <tr>
    <td style="width:60%;">
      {% include about/skills.html title="Languages Skills" source=site.data.language-skills %}
    </td>
    <td style="width:40%;">
      <!-- 빈 공간 -->
    </td>
  </tr>
</table>

<div class="row">
{% include about/timeline.html %}
</div>