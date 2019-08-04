---
layout: page
title: About
---

<table>
{% for player in site.data.sampledata %}
  <tr>
    {% for opponent in player %}
    <td>
      {{ opponent }}
    </td>
  </tr>
{% endfor %}
</table>