---
layout: page
title: Sample data
---

<table>
{% for player in site.data.sampledata %}
  <tr>
    {% for opponent in player %}
    <td>
      {{ opponent[1]}}
    </td>
    {% endfor %}
  </tr>
{% endfor %}
</table>