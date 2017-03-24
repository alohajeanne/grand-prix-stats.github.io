---
title: List of Formula 1® Races by Jean-Marc Gounon
layout: page
collectionName: drivers
collectionId: gounon
---

{% assign url_split = page.url | split: "/" %}
<div id="collection-navigation">
<button onclick="selector.options[selector.selectedIndex-1].value && (window.location = selector.options[selector.selectedIndex-1].value);">&lt; Prev</button>
<button onclick="selector.options[selector.selectedIndex+1].value && (window.location = selector.options[selector.selectedIndex+1].value);">Next &gt;</button>
<select id="selector" onchange="this.options[this.selectedIndex].value && (window.location = this.options[this.selectedIndex].value);">
  {% for collectionId in site.data[page.collectionName].refs %}
    {% if collectionId == page.collectionId %}
      {% assign selected = "selected" %}
    {% else %}
      {% assign selected = "" %}
    {% endif %}
    {% assign profile = site.data[page.collectionName][collectionId].profile %}
    <option value="/f1/{{ page.collectionName }}/{{ collectionId }}/{{ url_split[4] }}" {{ selected }}>{{ profile.collection_name }}</option>
  {% endfor %}
</select>
</div>

| Season | Round | Name | Date | Grid | Final Position | Laps Completed | Time | Winning Driver | Winning Constructor |
|--|--|--|--|--|--|--|--|--|--|
| 1994 | 13 | 1994 Portuguese Grand Prix 🇵🇹 | 1994-09-25 | 26 | 15 | 67 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1994 | 12 | 1994 Italian Grand Prix 🇮🇹 | 1994-09-11 | 25 | R | 20 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1994 | 11 | 1994 Belgian Grand Prix 🇧🇪 | 1994-08-28 | 25 | 11 | 42 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1994 | 10 | 1994 Hungarian Grand Prix 🇭🇺 | 1994-08-14 | 26 | R | 9 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1994 | 9 | 1994 German Grand Prix 🇩🇪 | 1994-07-31 | 26 | R | 39 |   | Gerhard Berger 🇦🇹 | Ferrari 🇮🇹 |
| 1994 | 8 | 1994 British Grand Prix 🇬🇧 | 1994-07-10 | 26 | 16 | 57 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1994 | 7 | 1994 French Grand Prix 🇫🇷 | 1994-07-03 | 26 | 9 | 68 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1993 | 16 | 1993 Australian Grand Prix 🇦🇺 | 1993-11-07 | 22 | R | 34 |   | Ayrton Senna 🇧🇷 | McLaren 🇬🇧 |
| 1993 | 15 | 1993 Japanese Grand Prix 🇯🇵 | 1993-10-24 | 13 | R | 26 |   | Ayrton Senna 🇧🇷 | McLaren 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 9 |  |  | 9 | 4 | 9 |  |  |  |
| **Total Sum** | 101.000 |  |  | 215.000 | 51.000 | 362.000 |  |  |  |
| **Mean μ (Average)** | 11.222 |  |  | 23.889 | 12.750 | 40.222 |  |  |  |
| **Maximum** | 16.000 |  |  | 26.000 | 16.000 | 68.000 |  |  |  |
| **75th Percentile** | 13.000 |  |  | 26.000 | 16.000 | 57.000 |  |  |  |
| **Median** | 11.000 |  |  | 26.000 | 15.000 | 39.000 |  |  |  |
| **25th Percentile** | 9.000 |  |  | 25.000 | 11.000 | 26.000 |  |  |  |
| **Minimum** | 7.000 |  |  | 13.000 | 9.000 | 9.000 |  |  |  |
| **Variance** | 8.395 |  |  | 16.321 | 8.188 | 377.728 |  |  |  |
| **Standard Deviation σ** | 2.897 |  |  | 4.040 | 2.861 | 19.435 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
