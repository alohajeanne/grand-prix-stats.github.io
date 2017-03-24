---
title: List of Formula 1® Races by Mike MacDowel
layout: page
collectionName: drivers
collectionId: macdowel
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
| 1957 | 4 | 1957 French Grand Prix 🇫🇷 | 1957-07-07 | 15 | 7 | 68 |   | Juan Fangio 🇦🇷 | Maserati 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 1 |  |  | 1 | 1 | 1 |  |  |  |
| **Total Sum** | 4.000 |  |  | 15.000 | 7.000 | 68.000 |  |  |  |
| **Mean μ (Average)** | 4.000 |  |  | 15.000 | 7.000 | 68.000 |  |  |  |
| **Maximum** | 4.000 |  |  | 15.000 | 7.000 | 68.000 |  |  |  |
| **75th Percentile** | 4.000 |  |  | 15.000 | 7.000 | 68.000 |  |  |  |
| **Median** | 4.000 |  |  | 15.000 | 7.000 | 68.000 |  |  |  |
| **25th Percentile** | 4.000 |  |  | 15.000 | 7.000 | 68.000 |  |  |  |
| **Minimum** | 4.000 |  |  | 15.000 | 7.000 | 68.000 |  |  |  |
| **Variance** |  |  |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
