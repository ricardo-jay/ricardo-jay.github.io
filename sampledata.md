---
layout: page
title: Sample data
---

<table>
{% for player in site.data.sampledata %}
  
  {% if forloop.first == true %}
  <tr>
    {% for opponent in player %}
    <td>
      {{ opponent[0]}}
    </td>
    {% endfor %}
  </tr>
  {% endif %}
  <tr>
    {% for opponent in player %}
    <td>
      {{ opponent[1]}}
    </td>
    {% endfor %}
  </tr>
{% endfor %}
</table>