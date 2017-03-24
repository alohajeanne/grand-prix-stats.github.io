---
title: List of Formula 1® Races by Jimmy Jackson
layout: page
collectionName: drivers
collectionId: jackson
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
| 1954 | 2 | 1954 Indianapolis 500 🇺🇸 | 1954-05-31 | 8 | 15 | 196 |   | Bill Vukovich 🇺🇸 | Kurtis Kraft 🇺🇸 |
| 1950 | 3 | 1950 Indianapolis 500 🇺🇸 | 1950-05-30 | 32 | R | 52 |   | Johnnie Parsons 🇺🇸 | Kurtis Kraft 🇺🇸 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 2 |  |  | 2 | 1 | 2 |  |  |  |
| **Total Sum** | 5.000 |  |  | 40.000 | 15.000 | 248.000 |  |  |  |
| **Mean μ (Average)** | 2.500 |  |  | 20.000 | 15.000 | 124.000 |  |  |  |
| **Maximum** | 3.000 |  |  | 32.000 | 15.000 | 196.000 |  |  |  |
| **75th Percentile** | 3.000 |  |  | 32.000 | 15.000 | 196.000 |  |  |  |
| **Median** | 3.000 |  |  | 32.000 | 15.000 | 196.000 |  |  |  |
| **25th Percentile** | 2.000 |  |  | 8.000 | 15.000 | 52.000 |  |  |  |
| **Minimum** | 2.000 |  |  | 8.000 | 15.000 | 52.000 |  |  |  |
| **Variance** | 0.250 |  |  | 144.000 |  | 5184.000 |  |  |  |
| **Standard Deviation σ** | 0.500 |  |  | 12.000 |  | 72.000 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
