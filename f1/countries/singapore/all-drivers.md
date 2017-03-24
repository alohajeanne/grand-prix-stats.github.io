---
title: List of All Formula 1® Drivers that Have Raced in Singapore by Number of Times
layout: page
collectionName: countries
collectionId: singapore
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
| Fernando Alonso 🇪🇸 | 9 |
| Jenson Button 🇬🇧 | 9 |
| Lewis Hamilton 🇬🇧 | 9 |
| Nico Rosberg 🇩🇪 | 9 |
| Sebastian Vettel 🇩🇪 | 9 |
| Felipe Massa 🇧🇷 | 8 |
| Kimi Räikkönen 🇫🇮 | 7 |
| Adrian Sutil 🇩🇪 | 6 |
| Daniel Ricciardo 🇦🇺 | 6 |
| Mark Webber 🇦🇺 | 6 |
| Nico Hülkenberg 🇩🇪 | 6 |
| Romain Grosjean 🇫🇷 | 6 |
| Sergio Pérez 🇲🇽 | 6 |
| Heikki Kovalainen 🇫🇮 | 5 |
| Pastor Maldonado 🇻🇪 | 5 |
| Timo Glock 🇩🇪 | 5 |
| Jarno Trulli 🇮🇹 | 4 |
| Kamui Kobayashi 🇯🇵 | 4 |
| Rubens Barrichello 🇧🇷 | 4 |
| Valtteri Bottas 🇫🇮 | 4 |
| Bruno Senna 🇧🇷 | 3 |
| Daniil Kvyat 🇷🇺 | 3 |
| Esteban Gutiérrez 🇲🇽 | 3 |
| Jaime Alguersuari 🇪🇸 | 3 |
| Jean-Éric Vergne 🇫🇷 | 3 |
| Marcus Ericsson 🇸🇪 | 3 |
| Michael Schumacher 🇩🇪 | 3 |
| Nick Heidfeld 🇩🇪 | 3 |
| Paul di Resta 🇬🇧 | 3 |
| Robert Kubica 🇵🇱 | 3 |
| Sébastien Buemi 🇨🇭 | 3 |
| Vitaly Petrov 🇷🇺 | 3 |
| Vitantonio Liuzzi 🇮🇹 | 3 |
| Carlos Sainz 🇪🇸 | 2 |
| Charles Pic 🇫🇷 | 2 |
| Felipe Nasr 🇧🇷 | 2 |
| Giancarlo Fisichella 🇮🇹 | 2 |
| Jules Bianchi 🇫🇷 | 2 |
| Kazuki Nakajima 🇯🇵 | 2 |
| Kevin Magnussen 🇩🇰 | 2 |
| Max Chilton 🇬🇧 | 2 |
| Max Verstappen 🇳🇱 | 2 |
| Alexander Rossi 🇺🇸 | 1 |
| Christian Klien 🇦🇹 | 1 |
| David Coulthard 🇬🇧 | 1 |
| Esteban Ocon 🇫🇷 | 1 |
| Giedo van der Garde 🇳🇱 | 1 |
| Jérôme d'Ambrosio 🇧🇪 | 1 |
| Jolyon Palmer 🇬🇧 | 1 |
| Lucas di Grassi 🇧🇷 | 1 |
| Narain Karthikeyan 🇮🇳 | 1 |
| Nelson Piquet Jr. 🇧🇷 | 1 |
| Pascal Wehrlein 🇩🇪 | 1 |
| Pedro de la Rosa 🇪🇸 | 1 |
| Sébastien Bourdais 🇫🇷 | 1 |
| Will Stevens 🇬🇧 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 56 |
| **Total Sum** | 198.000 |
| **Mean μ (Average)** | 3.536 |
| **Maximum** | 9.000 |
| **75th Percentile** | 5.000 |
| **Median** | 3.000 |
| **25th Percentile** | 2.000 |
| **Minimum** | 1.000 |
| **Variance** | 6.070 |
| **Standard Deviation σ** | 2.464 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
