---
title: List of All Formula 1® Drivers that Have Raced at Phoenix street circuit
layout: page
collectionName: circuits
collectionId: phoenix
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
| Aguri Suzuki 🇯🇵 | 3 |
| Alain Prost 🇫🇷 | 3 |
| Andrea de Cesaris 🇮🇹 | 3 |
| Ayrton Senna 🇧🇷 | 3 |
| Bertrand Gachot 🇧🇪 | 3 |
| Gabriele Tarquini 🇮🇹 | 3 |
| Gerhard Berger 🇦🇹 | 3 |
| Ivan Capelli 🇮🇹 | 3 |
| Maurício Gugelmin 🇧🇷 | 3 |
| Michele Alboreto 🇮🇹 | 3 |
| Nelson Piquet 🇧🇷 | 3 |
| Nicola Larini 🇮🇹 | 3 |
| Nigel Mansell 🇬🇧 | 3 |
| Olivier Grouillard 🇫🇷 | 3 |
| Pierluigi Martini 🇮🇹 | 3 |
| Riccardo Patrese 🇮🇹 | 3 |
| Roberto Moreno 🇧🇷 | 3 |
| Satoru Nakajima 🇯🇵 | 3 |
| Stefan Johansson 🇸🇪 | 3 |
| Stefano Modena 🇮🇹 | 3 |
| Thierry Boutsen 🇧🇪 | 3 |
| Alessandro Nannini 🇮🇹 | 2 |
| Alex Caffi 🇮🇹 | 2 |
| Bernd Schneider 🇩🇪 | 2 |
| Derek Warwick 🇬🇧 | 2 |
| Éric Bernard 🇫🇷 | 2 |
| Gianni Morbidelli 🇮🇹 | 2 |
| Gregor Foitek 🇨🇭 | 2 |
| Jean Alesi 🇫🇷 | 2 |
| Jyrki Järvilehto 🇫🇮 | 2 |
| Martin Brundle 🇬🇧 | 2 |
| Philippe Alliot 🇫🇷 | 2 |
| Yannick Dalmas 🇫🇷 | 2 |
| Christian Danner 🇩🇪 | 1 |
| Claudio Langes 🇮🇹 | 1 |
| Eddie Cheever 🇺🇸 | 1 |
| Emanuele Pirro 🇮🇹 | 1 |
| Eric van de Poele 🇧🇪 | 1 |
| Érik Comas 🇫🇷 | 1 |
| Gary Brabham 🇦🇺 | 1 |
| Joachim Winkelhock 🇩🇪 | 1 |
| Johnny Herbert 🇬🇧 | 1 |
| Jonathan Palmer 🇬🇧 | 1 |
| Julian Bailey 🇬🇧 | 1 |
| Luis Pérez-Sala 🇪🇸 | 1 |
| Mark Blundell 🇬🇧 | 1 |
| Martin Donnelly 🇬🇧 | 1 |
| Mika Häkkinen 🇫🇮 | 1 |
| Paolo Barilla 🇮🇹 | 1 |
| Pedro Chaves 🇵🇹 | 1 |
| Piercarlo Ghinzani 🇮🇹 | 1 |
| Pierre-Henri Raphanel 🇫🇷 | 1 |
| René Arnoux 🇫🇷 | 1 |
| Volker Weidler 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 54 |
| **Total Sum** | 108.000 |
| **Mean μ (Average)** | 2.000 |
| **Maximum** | 3.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.778 |
| **Standard Deviation σ** | 0.882 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
