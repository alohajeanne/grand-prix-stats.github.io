---
title: List of Formula 1® Races by Stoffel Vandoorne
layout: page
collectionName: drivers
collectionId: vandoorne
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

| Season | Round | Name | Date | Grid | Final Position | Points | Laps Completed | Time | Constructor | Teammate | Teammate Grid | Teammate Final Position |
|--|--|--|--|--|--|--|--|--|--|--|--|--|
| 2016 | 2 | 2016 Bahrain Grand Prix 🇧🇭 | 2016-04-03 | 12 | 10 | 1.0 | 56 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 14 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 1 |  |  | 1 | 1 | 1 | 1 |  |  |  | 1 |  |
| **Total Sum** | 2.000 |  |  | 12.000 | 10.000 | 1.000 | 56.000 |  |  |  | 14.000 |  |
| **Mean μ (Average)** | 2.000 |  |  | 12.000 | 10.000 | 1.000 | 56.000 |  |  |  | 14.000 |  |
| **Maximum** | 2.000 |  |  | 12.000 | 10.000 | 1.000 | 56.000 |  |  |  | 14.000 |  |
| **75th Percentile** | 2.000 |  |  | 12.000 | 10.000 | 1.000 | 56.000 |  |  |  | 14.000 |  |
| **Median** | 2.000 |  |  | 12.000 | 10.000 | 1.000 | 56.000 |  |  |  | 14.000 |  |
| **25th Percentile** | 2.000 |  |  | 12.000 | 10.000 | 1.000 | 56.000 |  |  |  | 14.000 |  |
| **Minimum** | 2.000 |  |  | 12.000 | 10.000 | 1.000 | 56.000 |  |  |  | 14.000 |  |
| **Variance** |  |  |  |  |  |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
