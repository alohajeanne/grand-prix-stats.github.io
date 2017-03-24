---
title: List of Formula 1® Races by Masahiro Hasemi
layout: page
collectionName: drivers
collectionId: hasemi
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
| 1976 | 16 | 1976 Japanese Grand Prix 🇯🇵 | 1976-10-24 | 10 | 11 | 66 |   | Mario Andretti 🇺🇸 | Team Lotus 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 1 |  |  | 1 | 1 | 1 |  |  |  |
| **Total Sum** | 16.000 |  |  | 10.000 | 11.000 | 66.000 |  |  |  |
| **Mean μ (Average)** | 16.000 |  |  | 10.000 | 11.000 | 66.000 |  |  |  |
| **Maximum** | 16.000 |  |  | 10.000 | 11.000 | 66.000 |  |  |  |
| **75th Percentile** | 16.000 |  |  | 10.000 | 11.000 | 66.000 |  |  |  |
| **Median** | 16.000 |  |  | 10.000 | 11.000 | 66.000 |  |  |  |
| **25th Percentile** | 16.000 |  |  | 10.000 | 11.000 | 66.000 |  |  |  |
| **Minimum** | 16.000 |  |  | 10.000 | 11.000 | 66.000 |  |  |  |
| **Variance** |  |  |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
