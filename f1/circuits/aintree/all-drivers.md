---
title: List of All Formula 1® Drivers that Have Raced at Aintree
layout: page
collectionName: circuits
collectionId: aintree
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
| Stirling Moss 🇬🇧 | 6 |
| Jack Brabham 🇦🇺 | 5 |
| Roy Salvadori 🇬🇧 | 5 |
| Harry Schell 🇺🇸 | 4 |
| Jack Fairman 🇬🇧 | 4 |
| Jo Bonnier 🇸🇪 | 4 |
| Keith Greene 🇬🇧 | 4 |
| Maurice Trintignant 🇫🇷 | 4 |
| Tony Brooks 🇬🇧 | 4 |
| Bruce McLaren 🇳🇿 | 3 |
| Graham Hill 🇬🇧 | 3 |
| Ian Burgess 🇬🇧 | 3 |
| Masten Gregory 🇺🇸 | 3 |
| Peter Collins 🇬🇧 | 3 |
| Carel Godin de Beaufort 🇳🇱 | 2 |
| Dan Gurney 🇺🇸 | 2 |
| Eugenio Castellotti 🇮🇹 | 2 |
| Henry Taylor 🇬🇧 | 2 |
| Horace Gould 🇬🇧 | 2 |
| Innes Ireland 🇬🇧 | 2 |
| Ivor Bueb 🇬🇧 | 2 |
| Jackie Lewis 🇬🇧 | 2 |
| Jean Behra 🇫🇷 | 2 |
| Jim Clark 🇬🇧 | 2 |
| John Surtees 🇬🇧 | 2 |
| Juan Fangio 🇦🇷 | 2 |
| Luigi Musso 🇮🇹 | 2 |
| Mike Hawthorn 🇬🇧 | 2 |
| Phil Hill 🇺🇸 | 2 |
| Richie Ginther 🇺🇸 | 2 |
| Tim Parnell 🇬🇧 | 2 |
| Tony Maggs 🇿🇦 | 2 |
| Trevor Taylor 🇬🇧 | 2 |
| Wolfgang Seidel 🇩🇪 | 2 |
| Alan Stacey 🇬🇧 | 1 |
| André Simon 🇫🇷 | 1 |
| Bill Moss 🇬🇧 | 1 |
| Bob Gerard 🇬🇧 | 1 |
| Brian Naylor 🇬🇧 | 1 |
| Carlos Menditeguy 🇦🇷 | 1 |
| Carroll Shelby 🇺🇸 | 1 |
| Chris Bristow 🇬🇧 | 1 |
| David Piper 🇬🇧 | 1 |
| Dennis Taylor 🇬🇧 | 1 |
| Fritz d'Orey 🇧🇷 | 1 |
| Gerry Ashmore 🇬🇧 | 1 |
| Giancarlo Baghetti 🇮🇹 | 1 |
| Hans Herrmann 🇩🇪 | 1 |
| Hernando da Silva Ramos 🇧🇷 | 1 |
| Jay Chamberlain 🇺🇸 | 1 |
| Jo Siffert 🇨🇭 | 1 |
| John Campbell-Jones 🇬🇧 | 1 |
| Karl Kling 🇩🇪 | 1 |
| Ken Wharton 🇬🇧 | 1 |
| Kenneth McAlpine 🇬🇧 | 1 |
| Lance Macklin 🇬🇧 | 1 |
| Les Leston 🇬🇧 | 1 |
| Leslie Marr 🇬🇧 | 1 |
| Lorenzo Bandini 🇮🇹 | 1 |
| Lucien Bianchi 🇧🇪 | 1 |
| Massimo Natili 🇮🇹 | 1 |
| Mike Parkes 🇬🇧 | 1 |
| Mike Sparken 🇫🇷 | 1 |
| Mike Taylor 🇬🇧 | 1 |
| Olivier Gendebien 🇧🇪 | 1 |
| Peter Ashdown 🇬🇧 | 1 |
| Peter Walker 🇬🇧 | 1 |
| Piero Taruffi 🇮🇹 | 1 |
| Robert Manzon 🇫🇷 | 1 |
| Roberto Mieres 🇦🇷 | 1 |
| Ron Flockhart 🇬🇧 | 1 |
| Stuart Lewis-Evans 🇬🇧 | 1 |
| Tony Marsh 🇬🇧 | 1 |
| Tony Rolt 🇬🇧 | 1 |
| Tony Settember 🇺🇸 | 1 |
| Tony Shelly 🇳🇿 | 1 |
| Wolfgang von Trips 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 77 |
| **Total Sum** | 138.000 |
| **Mean μ (Average)** | 1.792 |
| **Maximum** | 6.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.333 |
| **Standard Deviation σ** | 1.155 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
