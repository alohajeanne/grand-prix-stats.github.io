---
title: List of All Formula 1® Drivers that Have Raced at Donington Park
layout: page
collectionName: circuits
collectionId: donington
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
| Aguri Suzuki 🇯🇵 | 1 |
| Alain Prost 🇫🇷 | 1 |
| Alessandro Zanardi 🇮🇹 | 1 |
| Andrea de Cesaris 🇮🇹 | 1 |
| Ayrton Senna 🇧🇷 | 1 |
| Christian Fittipaldi 🇧🇷 | 1 |
| Damon Hill 🇬🇧 | 1 |
| Derek Warwick 🇬🇧 | 1 |
| Érik Comas 🇫🇷 | 1 |
| Fabrizio Barbazza 🇮🇹 | 1 |
| Gerhard Berger 🇦🇹 | 1 |
| Jean Alesi 🇫🇷 | 1 |
| Johnny Herbert 🇬🇧 | 1 |
| Jyrki Järvilehto 🇫🇮 | 1 |
| Karl Wendlinger 🇦🇹 | 1 |
| Luca Badoer 🇮🇹 | 1 |
| Mark Blundell 🇬🇧 | 1 |
| Martin Brundle 🇬🇧 | 1 |
| Michael Andretti 🇺🇸 | 1 |
| Michael Schumacher 🇩🇪 | 1 |
| Michele Alboreto 🇮🇹 | 1 |
| Philippe Alliot 🇫🇷 | 1 |
| Riccardo Patrese 🇮🇹 | 1 |
| Rubens Barrichello 🇧🇷 | 1 |
| Thierry Boutsen 🇧🇪 | 1 |
| Ukyo Katayama 🇯🇵 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 26 |
| **Total Sum** | 26.000 |
| **Mean μ (Average)** | 1.000 |
| **Maximum** | 1.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** |  |
| **Standard Deviation σ** |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
