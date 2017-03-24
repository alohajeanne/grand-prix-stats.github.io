---
title: List of Formula 1® Races by Mauri Rose
layout: page
collectionName: drivers
collectionId: rose
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
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30 | 5 | R | 126 |   | Lee Wallard 🇺🇸 | Kurtis Kraft 🇺🇸 |
| 1950 | 3 | 1950 Indianapolis 500 🇺🇸 | 1950-05-30 | 3 | 3 | 137 |   | Johnnie Parsons 🇺🇸 | Kurtis Kraft 🇺🇸 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 2 |  |  | 2 | 1 | 2 |  |  |  |
| **Total Sum** | 5.000 |  |  | 8.000 | 3.000 | 263.000 |  |  |  |
| **Mean μ (Average)** | 2.500 |  |  | 4.000 | 3.000 | 131.500 |  |  |  |
| **Maximum** | 3.000 |  |  | 5.000 | 3.000 | 137.000 |  |  |  |
| **75th Percentile** | 3.000 |  |  | 5.000 | 3.000 | 137.000 |  |  |  |
| **Median** | 3.000 |  |  | 5.000 | 3.000 | 137.000 |  |  |  |
| **25th Percentile** | 2.000 |  |  | 3.000 | 3.000 | 126.000 |  |  |  |
| **Minimum** | 2.000 |  |  | 3.000 | 3.000 | 126.000 |  |  |  |
| **Variance** | 0.250 |  |  | 1.000 |  | 30.250 |  |  |  |
| **Standard Deviation σ** | 0.500 |  |  | 1.000 |  | 5.500 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
