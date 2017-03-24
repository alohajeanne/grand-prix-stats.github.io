---
title: List of Formula 1® Races by Larry Crockett
layout: page
collectionName: drivers
collectionId: crockett
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
| 1954 | 2 | 1954 Indianapolis 500 🇺🇸 | 1954-05-31 | 25 | 9 | 200 | +7:07.24 | Bill Vukovich 🇺🇸 | Kurtis Kraft 🇺🇸 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 1 |  |  | 1 | 1 | 1 |  |  |  |
| **Total Sum** | 2.000 |  |  | 25.000 | 9.000 | 200.000 |  |  |  |
| **Mean μ (Average)** | 2.000 |  |  | 25.000 | 9.000 | 200.000 |  |  |  |
| **Maximum** | 2.000 |  |  | 25.000 | 9.000 | 200.000 |  |  |  |
| **75th Percentile** | 2.000 |  |  | 25.000 | 9.000 | 200.000 |  |  |  |
| **Median** | 2.000 |  |  | 25.000 | 9.000 | 200.000 |  |  |  |
| **25th Percentile** | 2.000 |  |  | 25.000 | 9.000 | 200.000 |  |  |  |
| **Minimum** | 2.000 |  |  | 25.000 | 9.000 | 200.000 |  |  |  |
| **Variance** |  |  |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
