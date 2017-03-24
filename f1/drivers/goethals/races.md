---
title: List of Formula 1® Races by Christian Goethals
layout: page
collectionName: drivers
collectionId: goethals
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
| 1958 | 8 | 1958 German Grand Prix 🇩🇪 | 1958-08-03 | 23 | R | 4 |   | Tony Brooks 🇬🇧 | Vanwall 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 1 |  |  | 1 |  | 1 |  |  |  |
| **Total Sum** | 8.000 |  |  | 23.000 |  | 4.000 |  |  |  |
| **Mean μ (Average)** | 8.000 |  |  | 23.000 |  | 4.000 |  |  |  |
| **Maximum** | 8.000 |  |  | 23.000 |  | 4.000 |  |  |  |
| **75th Percentile** | 8.000 |  |  | 23.000 |  | 4.000 |  |  |  |
| **Median** | 8.000 |  |  | 23.000 |  | 4.000 |  |  |  |
| **25th Percentile** | 8.000 |  |  | 23.000 |  | 4.000 |  |  |  |
| **Minimum** | 8.000 |  |  | 23.000 |  | 4.000 |  |  |  |
| **Variance** |  |  |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})