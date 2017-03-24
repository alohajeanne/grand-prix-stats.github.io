---
title: List of All Formula 1® Drivers that Have Raced at Autodromo Enzo e Dino Ferrari
layout: page
collectionName: circuits
collectionId: imola
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
| Michael Schumacher 🇩🇪 | 15 |
| Andrea de Cesaris 🇮🇹 | 14 |
| Michele Alboreto 🇮🇹 | 14 |
| Rubens Barrichello 🇧🇷 | 14 |
| Alain Prost 🇫🇷 | 13 |
| Gerhard Berger 🇦🇹 | 13 |
| Nigel Mansell 🇬🇧 | 13 |
| Riccardo Patrese 🇮🇹 | 13 |
| David Coulthard 🇬🇧 | 12 |
| Ayrton Senna 🇧🇷 | 11 |
| Giancarlo Fisichella 🇮🇹 | 11 |
| Jean Alesi 🇫🇷 | 11 |
| Nelson Piquet 🇧🇷 | 11 |
| Derek Warwick 🇬🇧 | 10 |
| Heinz-Harald Frentzen 🇩🇪 | 10 |
| Jacques Villeneuve 🇨🇦 | 10 |
| Jarno Trulli 🇮🇹 | 10 |
| Johnny Herbert 🇬🇧 | 10 |
| Martin Brundle 🇬🇧 | 10 |
| Mika Häkkinen 🇫🇮 | 10 |
| Olivier Panis 🇫🇷 | 10 |
| Ralf Schumacher 🇩🇪 | 10 |
| Thierry Boutsen 🇧🇪 | 10 |
| René Arnoux 🇫🇷 | 9 |
| Damon Hill 🇬🇧 | 8 |
| Eddie Cheever 🇺🇸 | 8 |
| Eddie Irvine 🇬🇧 | 8 |
| Jenson Button 🇬🇧 | 7 |
| Mika Salo 🇫🇮 | 7 |
| Nick Heidfeld 🇩🇪 | 7 |
| Philippe Alliot 🇫🇷 | 7 |
| Piercarlo Ghinzani 🇮🇹 | 7 |
| Pierluigi Martini 🇮🇹 | 7 |
| Aguri Suzuki 🇯🇵 | 6 |
| Bertrand Gachot 🇧🇪 | 6 |
| Elio de Angelis 🇮🇹 | 6 |
| Gabriele Tarquini 🇮🇹 | 6 |
| Ivan Capelli 🇮🇹 | 6 |
| Jacques Laffite 🇫🇷 | 6 |
| Jonathan Palmer 🇬🇧 | 6 |
| Jos Verstappen 🇳🇱 | 6 |
| Keke Rosberg 🇫🇮 | 6 |
| Kimi Räikkönen 🇫🇮 | 6 |
| Nicola Larini 🇮🇹 | 6 |
| Pedro Diniz 🇧🇷 | 6 |
| Ukyo Katayama 🇯🇵 | 6 |
| Alessandro Nannini 🇮🇹 | 5 |
| Alex Caffi 🇮🇹 | 5 |
| Bruno Giacomelli 🇮🇹 | 5 |
| Fernando Alonso 🇪🇸 | 5 |
| Juan Pablo Montoya 🇨🇴 | 5 |
| Jyrki Järvilehto 🇫🇮 | 5 |
| Manfred Winkelhock 🇩🇪 | 5 |
| Marc Surer 🇨🇭 | 5 |
| Mark Webber 🇦🇺 | 5 |
| Maurício Gugelmin 🇧🇷 | 5 |
| Patrick Tambay 🇫🇷 | 5 |
| Roberto Moreno 🇧🇷 | 5 |
| Satoru Nakajima 🇯🇵 | 5 |
| Stefan Johansson 🇸🇪 | 5 |
| Stefano Modena 🇮🇹 | 5 |
| Alexander Wurz 🇦🇹 | 4 |
| Érik Comas 🇫🇷 | 4 |
| Felipe Massa 🇧🇷 | 4 |
| Gianni Morbidelli 🇮🇹 | 4 |
| Karl Wendlinger 🇦🇹 | 4 |
| Luca Badoer 🇮🇹 | 4 |
| Olivier Grouillard 🇫🇷 | 4 |
| Takuma Sato 🇯🇵 | 4 |
| Teo Fabi 🇮🇹 | 4 |
| Alan Jones 🇦🇺 | 3 |
| Christian Danner 🇩🇪 | 3 |
| Christian Fittipaldi 🇧🇷 | 3 |
| Didier Pironi 🇫🇷 | 3 |
| Eliseo Salazar 🇨🇱 | 3 |
| Éric Bernard 🇫🇷 | 3 |
| Gilles Villeneuve 🇨🇦 | 3 |
| Jean-Pierre Jarier 🇫🇷 | 3 |
| John Watson 🇬🇧 | 3 |
| Mark Blundell 🇬🇧 | 3 |
| Mauro Baldi 🇮🇹 | 3 |
| Niki Lauda 🇦🇹 | 3 |
| Pedro de la Rosa 🇪🇸 | 3 |
| Philippe Streiff 🇫🇷 | 3 |
| Yannick Dalmas 🇫🇷 | 3 |
| Adrián Campos 🇪🇸 | 2 |
| Alessandro Zanardi 🇮🇹 | 2 |
| Andrea Montermini 🇮🇹 | 2 |
| Brian Henton 🇬🇧 | 2 |
| Carlos Reutemann 🇦🇷 | 2 |
| Chico Serra 🇧🇷 | 2 |
| Christian Klien 🇦🇹 | 2 |
| Christijan Albers 🇳🇱 | 2 |
| Cristiano da Matta 🇧🇷 | 2 |
| David Brabham 🇦🇺 | 2 |
| Derek Daly 🇮🇪 | 2 |
| Emanuele Pirro 🇮🇹 | 2 |
| Enrique Bernoldi 🇧🇷 | 2 |
| Eric van de Poele 🇧🇪 | 2 |
| Fabrizio Barbazza 🇮🇹 | 2 |
| François Hesnault 🇫🇷 | 2 |
| Gastón Mazzacane 🇦🇷 | 2 |
| Gregor Foitek 🇨🇭 | 2 |
| Hector Rebaque 🇲🇽 | 2 |
| Jan Lammers 🇳🇱 | 2 |
| Jan Magnussen 🇩🇰 | 2 |
| Jean-Pierre Jabouille 🇫🇷 | 2 |
| Johnny Cecotto 🇻🇪 | 2 |
| Julian Bailey 🇬🇧 | 2 |
| Luis Pérez-Sala 🇪🇸 | 2 |
| Marc Gené 🇪🇸 | 2 |
| Mario Andretti 🇺🇸 | 2 |
| Paul Belmondo 🇫🇷 | 2 |
| Pedro Lamy 🇵🇹 | 2 |
| Ricardo Rosset 🇧🇷 | 2 |
| Shinji Nakano 🇯🇵 | 2 |
| Stefan Bellof 🇩🇪 | 2 |
| Tiago Monteiro 🇵🇹 | 2 |
| Toranosuke Takagi 🇯🇵 | 2 |
| Vitantonio Liuzzi 🇮🇹 | 2 |
| Alex Yoong 🇲🇾 | 1 |
| Allan McNish 🇬🇧 | 1 |
| Andrea Chiesa 🇨🇭 | 1 |
| Antônio Pizzonia 🇧🇷 | 1 |
| Beppe Gabbiani 🇮🇹 | 1 |
| Bernd Schneider 🇩🇪 | 1 |
| Claudio Langes 🇮🇹 | 1 |
| Corrado Fabi 🇮🇹 | 1 |
| Danny Sullivan 🇺🇸 | 1 |
| Domenico Schiattarella 🇮🇹 | 1 |
| Emerson Fittipaldi 🇧🇷 | 1 |
| Esteban Tuero 🇦🇷 | 1 |
| Geoff Lees 🇬🇧 | 1 |
| Gianmaria Bruni 🇮🇹 | 1 |
| Giorgio Pantano 🇮🇹 | 1 |
| Huub Rothengatter 🇳🇱 | 1 |
| Jo Gartner 🇦🇹 | 1 |
| Joachim Winkelhock 🇩🇪 | 1 |
| Jody Scheckter 🇿🇦 | 1 |
| Johnny Dumfries 🇬🇧 | 1 |
| Justin Wilson 🇬🇧 | 1 |
| Luciano Burti 🇧🇷 | 1 |
| Martin Donnelly 🇬🇧 | 1 |
| Michael Andretti 🇺🇸 | 1 |
| Miguel Ángel Guerra 🇦🇷 | 1 |
| Narain Karthikeyan 🇮🇳 | 1 |
| Nico Rosberg 🇩🇪 | 1 |
| Olivier Beretta 🇲🇨 | 1 |
| Oscar Larrauri 🇦🇷 | 1 |
| Paolo Barilla 🇮🇹 | 1 |
| Pascal Fabre 🇫🇷 | 1 |
| Patrick Friesacher 🇦🇹 | 1 |
| Pedro Chaves 🇵🇹 | 1 |
| Perry McCarthy 🇬🇧 | 1 |
| Pierre-Henri Raphanel 🇫🇷 | 1 |
| Ralph Firman 🇮🇪 | 1 |
| Raul Boesel 🇧🇷 | 1 |
| Ricardo Zonta 🇧🇷 | 1 |
| Riccardo Paletti 🇮🇹 | 1 |
| Roberto Guerrero 🇨🇴 | 1 |
| Roland Ratzenberger 🇦🇹 | 1 |
| Rupert Keegan 🇬🇧 | 1 |
| Scott Speed 🇺🇸 | 1 |
| Siegfried Stohr 🇮🇹 | 1 |
| Slim Borgudd 🇸🇪 | 1 |
| Taki Inoue 🇯🇵 | 1 |
| Tarso Marques 🇧🇷 | 1 |
| Vittorio Brambilla 🇮🇹 | 1 |
| Volker Weidler 🇩🇪 | 1 |
| Yuji Ide 🇯🇵 | 1 |
| Zsolt Baumgartner 🇭🇺 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 171 |
| **Total Sum** | 695.000 |
| **Mean μ (Average)** | 4.064 |
| **Maximum** | 15.000 |
| **75th Percentile** | 6.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 12.703 |
| **Standard Deviation σ** | 3.564 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
