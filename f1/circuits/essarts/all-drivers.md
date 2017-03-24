---
title: List of All Formula 1® Drivers that Have Raced at Rouen-Les-Essarts
layout: page
collectionName: circuits
collectionId: essarts
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
| Jack Brabham 🇦🇺 | 5 |
| Maurice Trintignant 🇫🇷 | 4 |
| Bruce McLaren 🇳🇿 | 3 |
| Graham Hill 🇬🇧 | 3 |
| Harry Schell 🇺🇸 | 3 |
| Jo Siffert 🇨🇭 | 3 |
| John Surtees 🇬🇧 | 3 |
| Chris Amon 🇳🇿 | 2 |
| Dan Gurney 🇺🇸 | 2 |
| Innes Ireland 🇬🇧 | 2 |
| Jean Behra 🇫🇷 | 2 |
| Jim Clark 🇬🇧 | 2 |
| Mike Hawthorn 🇬🇧 | 2 |
| Peter Arundell 🇬🇧 | 2 |
| Peter Collins 🇬🇧 | 2 |
| Richie Ginther 🇺🇸 | 2 |
| Roy Salvadori 🇬🇧 | 2 |
| Trevor Taylor 🇬🇧 | 2 |
| Alberto Ascari 🇮🇹 | 1 |
| Bob Anderson 🇬🇧 | 1 |
| Carel Godin de Beaufort 🇳🇱 | 1 |
| Carlo Abate 🇮🇹 | 1 |
| Carlos Menditeguy 🇦🇷 | 1 |
| Colin Davis 🇬🇧 | 1 |
| Denny Hulme 🇳🇿 | 1 |
| Franco Comotti 🇮🇹 | 1 |
| Herbert MacKay-Fraser 🇺🇸 | 1 |
| Horace Gould 🇬🇧 | 1 |
| Ian Burgess 🇬🇧 | 1 |
| Jackie Lewis 🇬🇧 | 1 |
| Jackie Stewart 🇬🇧 | 1 |
| Jacky Ickx 🇧🇪 | 1 |
| Jean-Pierre Beltoise 🇫🇷 | 1 |
| Jo Bonnier 🇸🇪 | 1 |
| Jo Schlesser 🇫🇷 | 1 |
| Jochen Rindt 🇦🇹 | 1 |
| Johnny Claes 🇧🇪 | 1 |
| Johnny Servoz-Gavin 🇫🇷 | 1 |
| Juan Fangio 🇦🇷 | 1 |
| Lance Macklin 🇬🇧 | 1 |
| Lorenzo Bandini 🇮🇹 | 1 |
| Louis Rosier 🇫🇷 | 1 |
| Luigi Musso 🇮🇹 | 1 |
| Masten Gregory 🇺🇸 | 1 |
| Mike Hailwood 🇬🇧 | 1 |
| Mike MacDowel 🇬🇧 | 1 |
| Nino Farina 🇮🇹 | 1 |
| Pedro Rodríguez 🇲🇽 | 1 |
| Peter Hirt 🇨🇭 | 1 |
| Peter Whitehead 🇬🇧 | 1 |
| Phil Hill 🇺🇸 | 1 |
| Philippe Étancelin 🇫🇷 | 1 |
| Piero Carini 🇮🇹 | 1 |
| Piero Taruffi 🇮🇹 | 1 |
| Piers Courage 🇬🇧 | 1 |
| Prince Bira 🇹🇭 | 1 |
| Richard Attwood 🇬🇧 | 1 |
| Robert Manzon 🇫🇷 | 1 |
| Ron Flockhart 🇬🇧 | 1 |
| Rudi Fischer 🇨🇭 | 1 |
| Stuart Lewis-Evans 🇬🇧 | 1 |
| Tony Maggs 🇿🇦 | 1 |
| Tony Marsh 🇬🇧 | 1 |
| Toulo de Graffenried 🇨🇭 | 1 |
| Vic Elford 🇬🇧 | 1 |
| Yves Cabantous 🇫🇷 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 66 |
| **Total Sum** | 94.000 |
| **Mean μ (Average)** | 1.424 |
| **Maximum** | 5.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.669 |
| **Standard Deviation σ** | 0.818 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
