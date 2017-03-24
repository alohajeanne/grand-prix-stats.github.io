---
title: List of All Formula 1® Drivers that Have Raced at Autódromo Internacional Nelson Piquet
layout: page
collectionName: circuits
collectionId: jacarepagua
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
| Riccardo Patrese 🇮🇹 | 10 |
| Alain Prost 🇫🇷 | 9 |
| Andrea de Cesaris 🇮🇹 | 9 |
| Eddie Cheever 🇺🇸 | 9 |
| Nelson Piquet 🇧🇷 | 9 |
| Nigel Mansell 🇬🇧 | 9 |
| Michele Alboreto 🇮🇹 | 8 |
| René Arnoux 🇫🇷 | 8 |
| Derek Warwick 🇬🇧 | 7 |
| Jacques Laffite 🇫🇷 | 7 |
| Ayrton Senna 🇧🇷 | 6 |
| Elio de Angelis 🇮🇹 | 6 |
| Keke Rosberg 🇫🇮 | 6 |
| Patrick Tambay 🇫🇷 | 6 |
| Piercarlo Ghinzani 🇮🇹 | 6 |
| Thierry Boutsen 🇧🇪 | 6 |
| Gerhard Berger 🇦🇹 | 5 |
| Jonathan Palmer 🇬🇧 | 5 |
| Martin Brundle 🇬🇧 | 5 |
| Niki Lauda 🇦🇹 | 5 |
| Stefan Johansson 🇸🇪 | 5 |
| Alessandro Nannini 🇮🇹 | 4 |
| Jean-Pierre Jarier 🇫🇷 | 4 |
| John Watson 🇬🇧 | 4 |
| Manfred Winkelhock 🇩🇪 | 4 |
| Marc Surer 🇨🇭 | 4 |
| Mauro Baldi 🇮🇹 | 4 |
| Philippe Alliot 🇫🇷 | 4 |
| Teo Fabi 🇮🇹 | 4 |
| Alan Jones 🇦🇺 | 3 |
| Alex Caffi 🇮🇹 | 3 |
| Bruno Giacomelli 🇮🇹 | 3 |
| Carlos Reutemann 🇦🇷 | 3 |
| Chico Serra 🇧🇷 | 3 |
| Christian Danner 🇩🇪 | 3 |
| Didier Pironi 🇫🇷 | 3 |
| Eliseo Salazar 🇨🇱 | 3 |
| Gilles Villeneuve 🇨🇦 | 3 |
| Ivan Capelli 🇮🇹 | 3 |
| Philippe Streiff 🇫🇷 | 3 |
| Satoru Nakajima 🇯🇵 | 3 |
| Adrián Campos 🇪🇸 | 2 |
| Bernd Schneider 🇩🇪 | 2 |
| Derek Daly 🇮🇪 | 2 |
| François Hesnault 🇫🇷 | 2 |
| Hector Rebaque 🇲🇽 | 2 |
| Jochen Mass 🇩🇪 | 2 |
| Johnny Cecotto 🇻🇪 | 2 |
| Luis Pérez-Sala 🇪🇸 | 2 |
| Mario Andretti 🇺🇸 | 2 |
| Maurício Gugelmin 🇧🇷 | 2 |
| Nicola Larini 🇮🇹 | 2 |
| Pierluigi Martini 🇮🇹 | 2 |
| Raul Boesel 🇧🇷 | 2 |
| Roberto Guerrero 🇨🇴 | 2 |
| Stefano Modena 🇮🇹 | 2 |
| Yannick Dalmas 🇫🇷 | 2 |
| Aguri Suzuki 🇯🇵 | 1 |
| Arturo Merzario 🇮🇹 | 1 |
| Beppe Gabbiani 🇮🇹 | 1 |
| Bertrand Gachot 🇧🇪 | 1 |
| Brett Lunger 🇺🇸 | 1 |
| Brian Henton 🇬🇧 | 1 |
| Clay Regazzoni 🇨🇭 | 1 |
| Corrado Fabi 🇮🇹 | 1 |
| Danny Ongais 🇺🇸 | 1 |
| Danny Sullivan 🇺🇸 | 1 |
| Divina Galica 🇬🇧 | 1 |
| Emerson Fittipaldi 🇧🇷 | 1 |
| Gabriele Tarquini 🇮🇹 | 1 |
| Gregor Foitek 🇨🇭 | 1 |
| Hans-Joachim Stuck 🇩🇪 | 1 |
| James Hunt 🇬🇧 | 1 |
| Jan Lammers 🇳🇱 | 1 |
| Joachim Winkelhock 🇩🇪 | 1 |
| Jody Scheckter 🇿🇦 | 1 |
| Johnny Dumfries 🇬🇧 | 1 |
| Johnny Herbert 🇬🇧 | 1 |
| Julian Bailey 🇬🇧 | 1 |
| Lamberto Leoni 🇮🇹 | 1 |
| Miguel Ángel Guerra 🇦🇷 | 1 |
| Olivier Grouillard 🇫🇷 | 1 |
| Oscar Larrauri 🇦🇷 | 1 |
| Pascal Fabre 🇫🇷 | 1 |
| Patrick Depailler 🇫🇷 | 1 |
| Pierre-Henri Raphanel 🇫🇷 | 1 |
| Ricardo Londoño 🇨🇴 | 1 |
| Ricardo Zunino 🇦🇷 | 1 |
| Riccardo Paletti 🇮🇹 | 1 |
| Roberto Moreno 🇧🇷 | 1 |
| Ronnie Peterson 🇸🇪 | 1 |
| Rupert Keegan 🇬🇧 | 1 |
| Siegfried Stohr 🇮🇹 | 1 |
| Slim Borgudd 🇸🇪 | 1 |
| Stefan Bellof 🇩🇪 | 1 |
| Vittorio Brambilla 🇮🇹 | 1 |
| Volker Weidler 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 97 |
| **Total Sum** | 286.000 |
| **Mean μ (Average)** | 2.948 |
| **Maximum** | 10.000 |
| **75th Percentile** | 4.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 5.863 |
| **Standard Deviation σ** | 2.421 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
