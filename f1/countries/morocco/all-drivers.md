---
title: List of All Formula 1® Drivers that Have Raced in Morocco by Number of Times
layout: page
collectionName: countries
collectionId: morocco
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
| André Guelfi 🇫🇷 | 1 |
| Bruce McLaren 🇳🇿 | 1 |
| Cliff Allison 🇬🇧 | 1 |
| François Picard 🇫🇷 | 1 |
| Gerino Gerini 🇮🇹 | 1 |
| Graham Hill 🇬🇧 | 1 |
| Hans Herrmann 🇩🇪 | 1 |
| Harry Schell 🇺🇸 | 1 |
| Jack Brabham 🇦🇺 | 1 |
| Jack Fairman 🇬🇧 | 1 |
| Jean Behra 🇫🇷 | 1 |
| Jo Bonnier 🇸🇪 | 1 |
| Masten Gregory 🇺🇸 | 1 |
| Maurice Trintignant 🇫🇷 | 1 |
| Mike Hawthorn 🇬🇧 | 1 |
| Olivier Gendebien 🇧🇪 | 1 |
| Phil Hill 🇺🇸 | 1 |
| Robert La Caze 🇫🇷 | 1 |
| Ron Flockhart 🇬🇧 | 1 |
| Roy Salvadori 🇬🇧 | 1 |
| Stirling Moss 🇬🇧 | 1 |
| Stuart Lewis-Evans 🇬🇧 | 1 |
| Tom Bridger 🇬🇧 | 1 |
| Tony Brooks 🇬🇧 | 1 |
| Wolfgang Seidel 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 25 |
| **Total Sum** | 25.000 |
| **Mean μ (Average)** | 1.000 |
| **Maximum** | 1.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** |  |
| **Standard Deviation σ** |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
