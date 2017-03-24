---
title: List of All Formula 1® Drivers that Have Raced at Sebring International Raceway
layout: page
collectionName: circuits
collectionId: sebring
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

| Driver | Times |
|--|--|
| Alan Stacey 🇬🇧 | 1 |
| Alessandro de Tomaso 🇦🇷 | 1 |
| Bob Said 🇺🇸 | 1 |
| Bruce McLaren 🇳🇿 | 1 |
| Cliff Allison 🇬🇧 | 1 |
| Fritz d'Orey 🇧🇷 | 1 |
| George Constantine 🇺🇸 | 1 |
| Harry Blanchard 🇺🇸 | 1 |
| Harry Schell 🇺🇸 | 1 |
| Innes Ireland 🇬🇧 | 1 |
| Jack Brabham 🇦🇺 | 1 |
| Maurice Trintignant 🇫🇷 | 1 |
| Phil Cade 🇺🇸 | 1 |
| Phil Hill 🇺🇸 | 1 |
| Rodger Ward 🇺🇸 | 1 |
| Roy Salvadori 🇬🇧 | 1 |
| Stirling Moss 🇬🇧 | 1 |
| Tony Brooks 🇬🇧 | 1 |
| Wolfgang von Trips 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 19 |
| **Total Sum** | 19.000 |
| **Mean μ (Average)** | 1.000 |
| **Maximum** | 1.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** |  |
| **Standard Deviation σ** |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
