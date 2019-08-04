---
layout: page
title: Sample data
---

<table>
{% for player in site.data.sampledata %}
  <tr>
    {% for opponent in player %}
    <td>
      {{ opponent.title }}
    </td>
    {% endfor %}
  </tr>
{% endfor %}
</table>