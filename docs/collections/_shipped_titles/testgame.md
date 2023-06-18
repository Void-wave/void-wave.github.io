---
title: Test Game
role: Gameplay Programmer
release-date: January 1999
---

## {{page.role}}

<table  id="shipped-title">
{% assign row = site.data.gamedata.testgame[0] %}
    {% for pair in row %}
        <tr>
            <th> {{pair[0]}}</th>
            <td> {{pair[1]}}</td>
        </tr>
    {% endfor %}
</table>

Test game for test site.