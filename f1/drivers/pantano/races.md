---
title: List of Formula 1® Races by Giorgio Pantano
layout: page
collectionName: drivers
collectionId: pantano
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
| 2004 | 15 | 2004 Italian Grand Prix 🇮🇹 | 2004-09-12 | 17 | R | 33 |   | Rubens Barrichello 🇧🇷 | Ferrari 🇮🇹 |
| 2004 | 14 | 2004 Belgian Grand Prix 🇧🇪 | 2004-08-29 | 19 | R | 0 |   | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2004 | 13 | 2004 Hungarian Grand Prix 🇭🇺 | 2004-08-15 | 17 | R | 48 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 12 | 2004 German Grand Prix 🇩🇪 | 2004-07-25 | 17 | 15 | 63 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 11 | 2004 British Grand Prix 🇬🇧 | 2004-07-11 | 14 | R | 47 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 10 | 2004 French Grand Prix 🇫🇷 | 2004-07-04 | 18 | 17 | 67 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 9 | 2004 United States Grand Prix 🇺🇸 | 2004-06-20 | 17 | R | 0 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 7 | 2004 European Grand Prix 🇩🇪 | 2004-05-30 | 15 | 13 | 58 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 6 | 2004 Monaco Grand Prix 🇲🇨 | 2004-05-23 | 18 | R | 12 |   | Jarno Trulli 🇮🇹 | Renault 🇫🇷 |
| 2004 | 5 | 2004 Spanish Grand Prix 🇪🇸 | 2004-05-09 | 19 | R | 51 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 4 | 2004 San Marino Grand Prix 🇮🇹 | 2004-04-25 | 15 | R | 6 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 3 | 2004 Bahrain Grand Prix 🇧🇭 | 2004-04-04 | 15 | 16 | 55 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 2 | 2004 Malaysian Grand Prix 🇲🇾 | 2004-03-21 | 18 | 13 | 54 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 1 | 2004 Australian Grand Prix 🇦🇺 | 2004-03-07 | 16 | 14 | 55 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 14 |  |  | 14 | 6 | 14 |  |  |  |
| **Total Sum** | 112.000 |  |  | 235.000 | 88.000 | 549.000 |  |  |  |
| **Mean μ (Average)** | 8.000 |  |  | 16.786 | 14.667 | 39.214 |  |  |  |
| **Maximum** | 15.000 |  |  | 19.000 | 17.000 | 67.000 |  |  |  |
| **75th Percentile** | 12.000 |  |  | 18.000 | 16.000 | 55.000 |  |  |  |
| **Median** | 9.000 |  |  | 17.000 | 15.000 | 51.000 |  |  |  |
| **25th Percentile** | 4.000 |  |  | 15.000 | 13.000 | 12.000 |  |  |  |
| **Minimum** | 1.000 |  |  | 14.000 | 13.000 |  |  |  |  |
| **Variance** | 20.000 |  |  | 2.311 | 2.222 | 545.883 |  |  |  |
| **Standard Deviation σ** | 4.472 |  |  | 1.520 | 1.491 | 23.364 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
