---
title: List of All Formula 1® Drivers that Have Raced at Valencia Street Circuit
layout: page
collectionName: circuits
collectionId: valencia
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
| Fernando Alonso 🇪🇸 | 5 |
| Heikki Kovalainen 🇫🇮 | 5 |
| Jenson Button 🇬🇧 | 5 |
| Lewis Hamilton 🇬🇧 | 5 |
| Mark Webber 🇦🇺 | 5 |
| Nico Rosberg 🇩🇪 | 5 |
| Sebastian Vettel 🇩🇪 | 5 |
| Timo Glock 🇩🇪 | 5 |
| Adrian Sutil 🇩🇪 | 4 |
| Felipe Massa 🇧🇷 | 4 |
| Jarno Trulli 🇮🇹 | 4 |
| Rubens Barrichello 🇧🇷 | 4 |
| Jaime Alguersuari 🇪🇸 | 3 |
| Kamui Kobayashi 🇯🇵 | 3 |
| Kimi Räikkönen 🇫🇮 | 3 |
| Michael Schumacher 🇩🇪 | 3 |
| Nick Heidfeld 🇩🇪 | 3 |
| Robert Kubica 🇵🇱 | 3 |
| Sébastien Buemi 🇨🇭 | 3 |
| Vitaly Petrov 🇷🇺 | 3 |
| Bruno Senna 🇧🇷 | 2 |
| Giancarlo Fisichella 🇮🇹 | 2 |
| Kazuki Nakajima 🇯🇵 | 2 |
| Narain Karthikeyan 🇮🇳 | 2 |
| Nico Hülkenberg 🇩🇪 | 2 |
| Pastor Maldonado 🇻🇪 | 2 |
| Paul di Resta 🇬🇧 | 2 |
| Pedro de la Rosa 🇪🇸 | 2 |
| Romain Grosjean 🇫🇷 | 2 |
| Sergio Pérez 🇲🇽 | 2 |
| Vitantonio Liuzzi 🇮🇹 | 2 |
| Charles Pic 🇫🇷 | 1 |
| Daniel Ricciardo 🇦🇺 | 1 |
| David Coulthard 🇬🇧 | 1 |
| Jean-Éric Vergne 🇫🇷 | 1 |
| Jérôme d'Ambrosio 🇧🇪 | 1 |
| Karun Chandhok 🇮🇳 | 1 |
| Luca Badoer 🇮🇹 | 1 |
| Lucas di Grassi 🇧🇷 | 1 |
| Nelson Piquet Jr. 🇧🇷 | 1 |
| Sébastien Bourdais 🇫🇷 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 41 |
| **Total Sum** | 112.000 |
| **Mean μ (Average)** | 2.732 |
| **Maximum** | 5.000 |
| **75th Percentile** | 4.000 |
| **Median** | 2.000 |
| **25th Percentile** | 2.000 |
| **Minimum** | 1.000 |
| **Variance** | 2.050 |
| **Standard Deviation σ** | 1.432 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
