---
title: List of Formula 1® Races by Mike Magill
layout: page
collectionName: drivers
collectionId: magill
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
| 1959 | 2 | 1959 Indianapolis 500 🇺🇸 | 1959-05-30 | 31 | R | 45 |   | Rodger Ward 🇺🇸 | Watson 🇺🇸 |
| 1958 | 4 | 1958 Indianapolis 500 🇺🇸 | 1958-05-30 | 31 | R | 136 |   | Jimmy Bryan 🇺🇸 | Epperly 🇺🇸 |
| 1957 | 3 | 1957 Indianapolis 500 🇺🇸 | 1957-05-30 | 18 | R | 101 |   | Sam Hanks 🇺🇸 | Epperly 🇺🇸 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 3 |  |  | 3 |  | 3 |  |  |  |
| **Total Sum** | 9.000 |  |  | 80.000 |  | 282.000 |  |  |  |
| **Mean μ (Average)** | 3.000 |  |  | 26.667 |  | 94.000 |  |  |  |
| **Maximum** | 4.000 |  |  | 31.000 |  | 136.000 |  |  |  |
| **75th Percentile** | 4.000 |  |  | 31.000 |  | 136.000 |  |  |  |
| **Median** | 3.000 |  |  | 31.000 |  | 101.000 |  |  |  |
| **25th Percentile** | 2.000 |  |  | 18.000 |  | 45.000 |  |  |  |
| **Minimum** | 2.000 |  |  | 18.000 |  | 45.000 |  |  |  |
| **Variance** | 0.667 |  |  | 37.556 |  | 1404.667 |  |  |  |
| **Standard Deviation σ** | 0.816 |  |  | 6.128 |  | 37.479 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
