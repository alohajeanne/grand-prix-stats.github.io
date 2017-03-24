---
title: List of All Formula 1® Drivers that Have Raced at Autodromo Nazionale di Monza
layout: page
collectionName: circuits
collectionId: monza
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
| Rubens Barrichello 🇧🇷 | 19 |
| Jenson Button 🇬🇧 | 17 |
| Michael Schumacher 🇩🇪 | 17 |
| Graham Hill 🇬🇧 | 16 |
| Riccardo Patrese 🇮🇹 | 16 |
| David Coulthard 🇬🇧 | 15 |
| Fernando Alonso 🇪🇸 | 15 |
| Jarno Trulli 🇮🇹 | 15 |
| Gerhard Berger 🇦🇹 | 14 |
| Jo Bonnier 🇸🇪 | 14 |
| Kimi Räikkönen 🇫🇮 | 14 |
| Michele Alboreto 🇮🇹 | 14 |
| Andrea de Cesaris 🇮🇹 | 13 |
| Felipe Massa 🇧🇷 | 13 |
| Giancarlo Fisichella 🇮🇹 | 13 |
| Jean Alesi 🇫🇷 | 13 |
| Maurice Trintignant 🇫🇷 | 13 |
| Nelson Piquet 🇧🇷 | 13 |
| Alain Prost 🇫🇷 | 12 |
| John Surtees 🇬🇧 | 12 |
| Mark Webber 🇦🇺 | 12 |
| Niki Lauda 🇦🇹 | 12 |
| Derek Warwick 🇬🇧 | 11 |
| Jacques Laffite 🇫🇷 | 11 |
| Nico Rosberg 🇩🇪 | 11 |
| Nigel Mansell 🇬🇧 | 11 |
| Clay Regazzoni 🇨🇭 | 10 |
| Emerson Fittipaldi 🇧🇷 | 10 |
| Jack Brabham 🇦🇺 | 10 |
| Jacky Ickx 🇧🇪 | 10 |
| Jo Siffert 🇨🇭 | 10 |
| Lewis Hamilton 🇬🇧 | 10 |
| Martin Brundle 🇬🇧 | 10 |
| Mika Häkkinen 🇫🇮 | 10 |
| Sebastian Vettel 🇩🇪 | 10 |
| Thierry Boutsen 🇧🇪 | 10 |
| Ayrton Senna 🇧🇷 | 9 |
| Bruce McLaren 🇳🇿 | 9 |
| Carlos Reutemann 🇦🇷 | 9 |
| Chris Amon 🇳🇿 | 9 |
| Dan Gurney 🇺🇸 | 9 |
| Denny Hulme 🇳🇿 | 9 |
| Eddie Irvine 🇬🇧 | 9 |
| Heinz-Harald Frentzen 🇩🇪 | 9 |
| Jackie Stewart 🇬🇧 | 9 |
| Jacques Villeneuve 🇨🇦 | 9 |
| Jean-Pierre Jarier 🇫🇷 | 9 |
| Johnny Herbert 🇬🇧 | 9 |
| Juan Fangio 🇦🇷 | 9 |
| Nick Heidfeld 🇩🇪 | 9 |
| Olivier Panis 🇫🇷 | 9 |
| Patrick Tambay 🇫🇷 | 9 |
| Pierluigi Martini 🇮🇹 | 9 |
| Ralf Schumacher 🇩🇪 | 9 |
| René Arnoux 🇫🇷 | 9 |
| Ronnie Peterson 🇸🇪 | 9 |
| Stirling Moss 🇬🇧 | 9 |
| Eddie Cheever 🇺🇸 | 8 |
| John Watson 🇬🇧 | 8 |
| Keke Rosberg 🇫🇮 | 8 |
| Mario Andretti 🇺🇸 | 8 |
| Philippe Alliot 🇫🇷 | 8 |
| Adrian Sutil 🇩🇪 | 7 |
| Alan Jones 🇦🇺 | 7 |
| Bruno Giacomelli 🇮🇹 | 7 |
| Damon Hill 🇬🇧 | 7 |
| Giancarlo Baghetti 🇮🇹 | 7 |
| Harry Schell 🇺🇸 | 7 |
| Ivan Capelli 🇮🇹 | 7 |
| Jean Behra 🇫🇷 | 7 |
| Jim Clark 🇬🇧 | 7 |
| Jos Verstappen 🇳🇱 | 7 |
| Mika Salo 🇫🇮 | 7 |
| Pedro de la Rosa 🇪🇸 | 7 |
| Phil Hill 🇺🇸 | 7 |
| Piercarlo Ghinzani 🇮🇹 | 7 |
| Richie Ginther 🇺🇸 | 7 |
| Rolf Stommelen 🇩🇪 | 7 |
| Stefan Johansson 🇸🇪 | 7 |
| Alberto Ascari 🇮🇹 | 6 |
| Alex Caffi 🇮🇹 | 6 |
| Arturo Merzario 🇮🇹 | 6 |
| Daniel Ricciardo 🇦🇺 | 6 |
| Elio de Angelis 🇮🇹 | 6 |
| Hans-Joachim Stuck 🇩🇪 | 6 |
| Heikki Kovalainen 🇫🇮 | 6 |
| Innes Ireland 🇬🇧 | 6 |
| James Hunt 🇬🇧 | 6 |
| Jean-Pierre Beltoise 🇫🇷 | 6 |
| Jochen Rindt 🇦🇹 | 6 |
| Jody Scheckter 🇿🇦 | 6 |
| Lorenzo Bandini 🇮🇹 | 6 |
| Luigi Villoresi 🇮🇹 | 6 |
| Marc Surer 🇨🇭 | 6 |
| Masten Gregory 🇺🇸 | 6 |
| Mike Hawthorn 🇬🇧 | 6 |
| Nico Hülkenberg 🇩🇪 | 6 |
| Nino Farina 🇮🇹 | 6 |
| Pedro Diniz 🇧🇷 | 6 |
| Roy Salvadori 🇬🇧 | 6 |
| Sergio Pérez 🇲🇽 | 6 |
| Ukyo Katayama 🇯🇵 | 6 |
| Vittorio Brambilla 🇮🇹 | 6 |
| Aguri Suzuki 🇯🇵 | 5 |
| Alessandro Nannini 🇮🇹 | 5 |
| Carlos Pace 🇧🇷 | 5 |
| Gabriele Tarquini 🇮🇹 | 5 |
| Henri Pescarolo 🇫🇷 | 5 |
| Jackie Oliver 🇬🇧 | 5 |
| Jonathan Palmer 🇬🇧 | 5 |
| Juan Pablo Montoya 🇨🇴 | 5 |
| Louis Rosier 🇫🇷 | 5 |
| Luigi Musso 🇮🇹 | 5 |
| Maurício Gugelmin 🇧🇷 | 5 |
| Mike Hailwood 🇬🇧 | 5 |
| Mike Spence 🇬🇧 | 5 |
| Nicola Larini 🇮🇹 | 5 |
| Pastor Maldonado 🇻🇪 | 5 |
| Patrick Depailler 🇫🇷 | 5 |
| Peter Collins 🇬🇧 | 5 |
| Piero Taruffi 🇮🇹 | 5 |
| Robert Kubica 🇵🇱 | 5 |
| Robert Manzon 🇫🇷 | 5 |
| Romain Grosjean 🇫🇷 | 5 |
| Satoru Nakajima 🇯🇵 | 5 |
| Stefano Modena 🇮🇹 | 5 |
| Takuma Sato 🇯🇵 | 5 |
| Teo Fabi 🇮🇹 | 5 |
| Timo Glock 🇩🇪 | 5 |
| Toulo de Graffenried 🇨🇭 | 5 |
| Vitantonio Liuzzi 🇮🇹 | 5 |
| Wolfgang von Trips 🇩🇪 | 5 |
| Alexander Wurz 🇦🇹 | 4 |
| André Simon 🇫🇷 | 4 |
| Bertrand Gachot 🇧🇪 | 4 |
| Brett Lunger 🇺🇸 | 4 |
| Érik Comas 🇫🇷 | 4 |
| Felice Bonetto 🇮🇹 | 4 |
| François Cevert 🇫🇷 | 4 |
| Gianni Morbidelli 🇮🇹 | 4 |
| Harald Ertl 🇦🇹 | 4 |
| Jack Fairman 🇬🇧 | 4 |
| Jochen Mass 🇩🇪 | 4 |
| Johnny Claes 🇧🇪 | 4 |
| José Froilán González 🇦🇷 | 4 |
| Jyrki Järvilehto 🇫🇮 | 4 |
| Kamui Kobayashi 🇯🇵 | 4 |
| Mark Blundell 🇬🇧 | 4 |
| Olivier Grouillard 🇫🇷 | 4 |
| Philippe Streiff 🇫🇷 | 4 |
| Roberto Moreno 🇧🇷 | 4 |
| Silvio Moser 🇨🇭 | 4 |
| Tim Schenken 🇦🇺 | 4 |
| Tony Brooks 🇬🇧 | 4 |
| Umberto Maglioli 🇮🇹 | 4 |
| Valtteri Bottas 🇫🇮 | 4 |
| Yannick Dalmas 🇫🇷 | 4 |
| Andrea de Adamich 🇮🇹 | 3 |
| Bob Anderson 🇬🇧 | 3 |
| Brian Henton 🇬🇧 | 3 |
| Bruno Senna 🇧🇷 | 3 |
| Carel Godin de Beaufort 🇳🇱 | 3 |
| Carroll Shelby 🇺🇸 | 3 |
| Chico Landi 🇧🇷 | 3 |
| Christian Danner 🇩🇪 | 3 |
| Christian Fittipaldi 🇧🇷 | 3 |
| Christian Klien 🇦🇹 | 3 |
| Daniil Kvyat 🇷🇺 | 3 |
| Derek Bell 🇬🇧 | 3 |
| Derek Daly 🇮🇪 | 3 |
| Didier Pironi 🇫🇷 | 3 |
| Emanuele Pirro 🇮🇹 | 3 |
| Éric Bernard 🇫🇷 | 3 |
| Esteban Gutiérrez 🇲🇽 | 3 |
| Eugenio Castellotti 🇮🇹 | 3 |
| Franco Rol 🇮🇹 | 3 |
| Giacomo Russo 🇮🇹 | 3 |
| Gilles Villeneuve 🇨🇦 | 3 |
| Giorgio Scarlatti 🇮🇹 | 3 |
| Giulio Cabianca 🇮🇹 | 3 |
| Hans Herrmann 🇩🇪 | 3 |
| Hector Rebaque 🇲🇽 | 3 |
| Horace Gould 🇬🇧 | 3 |
| Howden Ganley 🇳🇿 | 3 |
| Huub Rothengatter 🇳🇱 | 3 |
| Ian Burgess 🇬🇧 | 3 |
| Jaime Alguersuari 🇪🇸 | 3 |
| Jean-Éric Vergne 🇫🇷 | 3 |
| Jean-Pierre Jabouille 🇫🇷 | 3 |
| Ken Wharton 🇬🇧 | 3 |
| Louis Chiron 🇲🇨 | 3 |
| Luca Badoer 🇮🇹 | 3 |
| Ludovico Scarfiotti 🇮🇹 | 3 |
| Luigi Piotti 🇮🇹 | 3 |
| Manfred Winkelhock 🇩🇪 | 3 |
| Marc Gené 🇪🇸 | 3 |
| Marcus Ericsson 🇸🇪 | 3 |
| Mike Beuttler 🇬🇧 | 3 |
| Nanni Galli 🇮🇹 | 3 |
| Nino Vaccarella 🇮🇹 | 3 |
| Paul di Resta 🇬🇧 | 3 |
| Pedro Lamy 🇵🇹 | 3 |
| Pedro Rodríguez 🇲🇽 | 3 |
| Peter Gethin 🇬🇧 | 3 |
| Peter Revson 🇺🇸 | 3 |
| Peter Whitehead 🇬🇧 | 3 |
| Ricardo Zonta 🇧🇷 | 3 |
| Roberto Lippi 🇮🇹 | 3 |
| Roberto Mieres 🇦🇷 | 3 |
| Sakon Yamamoto 🇯🇵 | 3 |
| Sébastien Buemi 🇨🇭 | 3 |
| Tom Pryce 🇬🇧 | 3 |
| Vitaly Petrov 🇷🇺 | 3 |
| Alan Brown 🇬🇧 | 2 |
| Alessandro Zanardi 🇮🇹 | 2 |
| Alex Yoong 🇲🇾 | 2 |
| Alfonso Thiele 🇺🇸 | 2 |
| André Pilette 🇧🇪 | 2 |
| Antônio Pizzonia 🇧🇷 | 2 |
| Bernd Schneider 🇩🇪 | 2 |
| Brian Naylor 🇬🇧 | 2 |
| Bruce Halford 🇬🇧 | 2 |
| Carlos Sainz 🇪🇸 | 2 |
| Charles Pic 🇫🇷 | 2 |
| Chico Serra 🇧🇷 | 2 |
| Christijan Albers 🇳🇱 | 2 |
| Cliff Allison 🇬🇧 | 2 |
| David Brabham 🇦🇺 | 2 |
| David Hobbs 🇬🇧 | 2 |
| Edgar Barth 🇩🇪 | 2 |
| Élie Bayol 🇫🇷 | 2 |
| Eliseo Salazar 🇨🇱 | 2 |
| Eric van de Poele 🇧🇪 | 2 |
| Ernesto Prinoth 🇮🇹 | 2 |
| Felipe Nasr 🇧🇷 | 2 |
| Frank Gardner 🇦🇺 | 2 |
| Gaetano Starrabba 🇮🇹 | 2 |
| Gerino Gerini 🇮🇹 | 2 |
| Gerry Ashmore 🇬🇧 | 2 |
| Giovanni Lavaggi 🇮🇹 | 2 |
| Gunnar Nilsson 🇸🇪 | 2 |
| Hans von Stuck 🇩🇪 | 2 |
| Hernando da Silva Ramos 🇧🇷 | 2 |
| Ian Raby 🇬🇧 | 2 |
| Jérôme d'Ambrosio 🇧🇪 | 2 |
| John Fitch 🇺🇸 | 2 |
| John Miles 🇬🇧 | 2 |
| Jules Bianchi 🇫🇷 | 2 |
| Karl Kling 🇩🇪 | 2 |
| Karl Wendlinger 🇦🇹 | 2 |
| Kazuki Nakajima 🇯🇵 | 2 |
| Kenneth McAlpine 🇬🇧 | 2 |
| Kenny Acheson 🇬🇧 | 2 |
| Kevin Magnussen 🇩🇰 | 2 |
| Lance Macklin 🇬🇧 | 2 |
| Luis Pérez-Sala 🇪🇸 | 2 |
| Mário de Araújo Cabral 🇵🇹 | 2 |
| Mauro Baldi 🇮🇹 | 2 |
| Max Chilton 🇬🇧 | 2 |
| Max Verstappen 🇳🇱 | 2 |
| Narain Karthikeyan 🇮🇳 | 2 |
| Olivier Gendebien 🇧🇪 | 2 |
| Oscar Larrauri 🇦🇷 | 2 |
| Paco Godia 🇪🇸 | 2 |
| Pierre Levegh 🇫🇷 | 2 |
| Piers Courage 🇬🇧 | 2 |
| Prince Bira 🇹🇭 | 2 |
| Raul Boesel 🇧🇷 | 2 |
| Ricardo Rodríguez 🇲🇽 | 2 |
| Ricardo Rosset 🇧🇷 | 2 |
| Roberto Bussinello 🇮🇹 | 2 |
| Roberto Guerrero 🇨🇴 | 2 |
| Ron Flockhart 🇬🇧 | 2 |
| Ronnie Bucknum 🇺🇸 | 2 |
| Rupert Keegan 🇬🇧 | 2 |
| Sergio Mantovani 🇮🇹 | 2 |
| Shinji Nakano 🇯🇵 | 2 |
| Stuart Lewis-Evans 🇬🇧 | 2 |
| Tiago Monteiro 🇵🇹 | 2 |
| Tony Maggs 🇿🇦 | 2 |
| Tony Settember 🇺🇸 | 2 |
| Toranosuke Takagi 🇯🇵 | 2 |
| Trevor Taylor 🇬🇧 | 2 |
| Willy Mairesse 🇧🇪 | 2 |
| Wilson Fittipaldi 🇧🇷 | 2 |
| Wolfgang Seidel 🇩🇪 | 2 |
| Yves Cabantous 🇫🇷 | 2 |
| Zsolt Baumgartner 🇭🇺 | 2 |
| Adrián Campos 🇪🇸 | 1 |
| Alberto Colombo 🇮🇹 | 1 |
| Alberto Crespo 🇦🇷 | 1 |
| Alessandro Pesenti-Rossi 🇮🇹 | 1 |
| Alex Ribeiro 🇧🇷 | 1 |
| Alfonso de Portago 🇪🇸 | 1 |
| Allan McNish 🇬🇧 | 1 |
| Andrea Montermini 🇮🇹 | 1 |
| Anthony Davidson 🇬🇧 | 1 |
| Arthur Owen 🇬🇧 | 1 |
| Beppe Gabbiani 🇮🇹 | 1 |
| Bill Aston 🇬🇧 | 1 |
| Bob Bondurant 🇺🇸 | 1 |
| Bob Evans 🇬🇧 | 1 |
| Carlo Abate 🇮🇹 | 1 |
| Carlo Facetti 🇮🇹 | 1 |
| Carlo Franchi 🇮🇹 | 1 |
| Carlos Menditeguy 🇦🇷 | 1 |
| Charles de Tornaco 🇧🇪 | 1 |
| Chris Irwin 🇬🇧 | 1 |
| Claudio Langes 🇮🇹 | 1 |
| Clemar Bucci 🇦🇷 | 1 |
| Clemente Biondetti 🇮🇹 | 1 |
| Colin Davis 🇬🇧 | 1 |
| Consalvo Sanesi 🇮🇹 | 1 |
| Corrado Fabi 🇮🇹 | 1 |
| Cristiano da Matta 🇧🇷 | 1 |
| Cuth Harrison 🇬🇧 | 1 |
| Danny Sullivan 🇺🇸 | 1 |
| David Murray 🇬🇧 | 1 |
| David Purley 🇬🇧 | 1 |
| Dennis Poore 🇬🇧 | 1 |
| Dorino Serafini 🇮🇹 | 1 |
| Eitel Cantoni 🇺🇾 | 1 |
| Emanuele Naspetti 🇮🇹 | 1 |
| Emilio de Villota 🇪🇸 | 1 |
| Enrico Bertaggia 🇮🇹 | 1 |
| Enrique Bernoldi 🇧🇷 | 1 |
| Eric Brandon 🇬🇧 | 1 |
| Ernesto Brambilla 🇮🇹 | 1 |
| Esteban Ocon 🇫🇷 | 1 |
| Esteban Tuero 🇦🇷 | 1 |
| Fabrizio Barbazza 🇮🇹 | 1 |
| Franco Comotti 🇮🇹 | 1 |
| Franco Forini 🇨🇭 | 1 |
| François Hesnault 🇫🇷 | 1 |
| François Migault 🇫🇷 | 1 |
| Fred Gamble 🇺🇸 | 1 |
| Fred Wacker 🇺🇸 | 1 |
| Gastón Mazzacane 🇦🇷 | 1 |
| George Eaton 🇨🇦 | 1 |
| George Follmer 🇺🇸 | 1 |
| Gerhard Mitter 🇩🇪 | 1 |
| Gianmaria Bruni 🇮🇹 | 1 |
| Giedo van der Garde 🇳🇱 | 1 |
| Gijs van Lennep 🇳🇱 | 1 |
| Gino Bianco 🇧🇷 | 1 |
| Gino Munaron 🇮🇹 | 1 |
| Giorgio Bassi 🇮🇹 | 1 |
| Giorgio Francia 🇮🇹 | 1 |
| Giorgio Pantano 🇮🇹 | 1 |
| Giovanni de Riu 🇮🇹 | 1 |
| Günther Seiffert 🇩🇪 | 1 |
| Guy Edwards 🇬🇧 | 1 |
| Guy Ligier 🇫🇷 | 1 |
| Guy Mairesse 🇫🇷 | 1 |
| Hans Binder 🇦🇹 | 1 |
| Helmut Marko 🇦🇹 | 1 |
| Henri Louveau 🇫🇷 | 1 |
| Henry Taylor 🇬🇧 | 1 |
| Ian Ashley 🇬🇧 | 1 |
| Ian Scheckter 🇿🇦 | 1 |
| Ignazio Giunti 🇮🇹 | 1 |
| Jackie Lewis 🇬🇧 | 1 |
| Jacques Pollet 🇫🇷 | 1 |
| Jacques Swaters 🇺🇸 | 1 |
| Jan Lammers 🇳🇱 | 1 |
| Jan Magnussen 🇩🇰 | 1 |
| Jay Chamberlain 🇺🇸 | 1 |
| Jean Lucas 🇫🇷 | 1 |
| Jean-Christophe Boullion 🇫🇷 | 1 |
| Jean-Louis Schlesser 🇫🇷 | 1 |
| Jean-Marc Gounon 🇫🇷 | 1 |
| Jim Crawford 🇬🇧 | 1 |
| Jim Hall 🇺🇸 | 1 |
| Jo Gartner 🇦🇹 | 1 |
| John Love 🇿🇼 | 1 |
| Johnny Cecotto 🇻🇪 | 1 |
| Johnny Dumfries 🇬🇧 | 1 |
| Johnny Servoz-Gavin 🇫🇷 | 1 |
| Jolyon Palmer 🇬🇧 | 1 |
| Jorge Daponte 🇦🇷 | 1 |
| José Dolhem 🇫🇷 | 1 |
| Julian Bailey 🇬🇧 | 1 |
| Justin Wilson 🇬🇧 | 1 |
| Keith Greene 🇬🇧 | 1 |
| Ken Richardson 🇬🇧 | 1 |
| Kurt Kuhnke 🇩🇪 | 1 |
| Lamberto Leoni 🇮🇹 | 1 |
| Larry Perkins 🇦🇺 | 1 |
| Lella Lombardi 🇮🇹 | 1 |
| Leo Kinnunen 🇫🇮 | 1 |
| Les Leston 🇬🇧 | 1 |
| Loris Kessel 🇨🇭 | 1 |
| Lucas di Grassi 🇧🇷 | 1 |
| Luigi Fagioli 🇮🇹 | 1 |
| Marco Apicella 🇮🇹 | 1 |
| Maria de Filippis 🇮🇹 | 1 |
| Martin Donnelly 🇬🇧 | 1 |
| Massimiliano Papis 🇮🇹 | 1 |
| Massimo Natili 🇮🇹 | 1 |
| Menato Boffa 🇮🇹 | 1 |
| Michael Andretti 🇺🇸 | 1 |
| Michael Bartels 🇩🇪 | 1 |
| Michael Bleekemolen 🇳🇱 | 1 |
| Michael May 🇨🇭 | 1 |
| Mike Parkes 🇬🇧 | 1 |
| Mike Wilds 🇬🇧 | 1 |
| Nasif Estéfano 🇦🇷 | 1 |
| Nelson Piquet Jr. 🇧🇷 | 1 |
| Nicolas Kiesa 🇩🇰 | 1 |
| Onofre Marimón 🇦🇷 | 1 |
| Otto Stuppacher 🇦🇹 | 1 |
| Ottorino Volonterio 🇨🇭 | 1 |
| Paolo Barilla 🇮🇹 | 1 |
| Pascal Fabre 🇫🇷 | 1 |
| Pascal Wehrlein 🇩🇪 | 1 |
| Patrick Nève 🇧🇪 | 1 |
| Paul Belmondo 🇫🇷 | 1 |
| Paul Pietsch 🇩🇪 | 1 |
| Pedro Chaves 🇵🇹 | 1 |
| Peter Arundell 🇬🇧 | 1 |
| Philippe Étancelin 🇫🇷 | 1 |
| Piero Carini 🇮🇹 | 1 |
| Piero Drogo 🇮🇹 | 1 |
| Piero Dusio 🇮🇹 | 1 |
| Pierre-Henri Raphanel 🇫🇷 | 1 |
| Raymond Sommer 🇫🇷 | 1 |
| Reg Parnell 🇬🇧 | 1 |
| Reine Wisell 🇸🇪 | 1 |
| Renato Pirocchi 🇮🇹 | 1 |
| Renzo Zorzi 🇮🇹 | 1 |
| Richard Attwood 🇬🇧 | 1 |
| Rikky von Opel 🇱🇮 | 1 |
| Robert Doornbos 🇳🇱 | 1 |
| Roberto Merhi 🇪🇸 | 1 |
| Roelof Wunderink 🇳🇱 | 1 |
| Rudi Fischer 🇨🇭 | 1 |
| Scott Speed 🇺🇸 | 1 |
| Sébastien Bourdais 🇫🇷 | 1 |
| Siegfried Stohr 🇮🇹 | 1 |
| Slim Borgudd 🇸🇪 | 1 |
| Taki Inoue 🇯🇵 | 1 |
| Tarso Marques 🇧🇷 | 1 |
| Teddy Pilette 🇧🇪 | 1 |
| Tim Parnell 🇬🇧 | 1 |
| Tomáš Enge 🇨🇿 | 1 |
| Tommy Byrne 🇮🇪 | 1 |
| Tony Brise 🇬🇧 | 1 |
| Tony Gaze 🇦🇺 | 1 |
| Tony Shelly 🇳🇿 | 1 |
| Tony Trimmer 🇬🇧 | 1 |
| Vic Elford 🇬🇧 | 1 |
| Vic Wilson 🇬🇧 | 1 |
| Will Stevens 🇬🇧 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 453 |
| **Total Sum** | 1676.000 |
| **Mean μ (Average)** | 3.700 |
| **Maximum** | 19.000 |
| **75th Percentile** | 5.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 12.351 |
| **Standard Deviation σ** | 3.514 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
