---
title: List of Formula 1® Races by Peter Westbury
layout: page
collectionName: drivers
collectionId: westbury
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
| 1970 | 12 | 1970 United States Grand Prix 🇺🇸 | 1970-10-04 | 0 | F | 0 |   | Emerson Fittipaldi 🇧🇷 | Team Lotus 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 1 |  |  | 1 |  | 1 |  |  |  |
| **Total Sum** | 12.000 |  |  |  |  |  |  |  |  |
| **Mean μ (Average)** | 12.000 |  |  |  |  |  |  |  |  |
| **Maximum** | 12.000 |  |  |  |  |  |  |  |  |
| **75th Percentile** | 12.000 |  |  |  |  |  |  |  |  |
| **Median** | 12.000 |  |  |  |  |  |  |  |  |
| **25th Percentile** | 12.000 |  |  |  |  |  |  |  |  |
| **Minimum** | 12.000 |  |  |  |  |  |  |  |  |
| **Variance** |  |  |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})