---
title: List of All Formula 1® Drivers that Have Raced in USA by Number of Times
layout: page
collectionName: countries
collectionId: usa
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
| Jacques Laffite 🇫🇷 | 23 |
| Riccardo Patrese 🇮🇹 | 21 |
| Jean-Pierre Jarier 🇫🇷 | 20 |
| John Watson 🇬🇧 | 20 |
| Nelson Piquet 🇧🇷 | 20 |
| Mario Andretti 🇺🇸 | 19 |
| Niki Lauda 🇦🇹 | 19 |
| René Arnoux 🇫🇷 | 18 |
| Alain Prost 🇫🇷 | 17 |
| Andrea de Cesaris 🇮🇹 | 17 |
| Eddie Cheever 🇺🇸 | 16 |
| Emerson Fittipaldi 🇧🇷 | 16 |
| Keke Rosberg 🇫🇮 | 16 |
| Nigel Mansell 🇬🇧 | 16 |
| Carlos Reutemann 🇦🇷 | 15 |
| Clay Regazzoni 🇨🇭 | 15 |
| Graham Hill 🇬🇧 | 15 |
| Michele Alboreto 🇮🇹 | 15 |
| Alan Jones 🇦🇺 | 14 |
| Elio de Angelis 🇮🇹 | 14 |
| Jochen Mass 🇩🇪 | 14 |
| Jody Scheckter 🇿🇦 | 14 |
| Derek Warwick 🇬🇧 | 13 |
| Jenson Button 🇬🇧 | 13 |
| Patrick Tambay 🇫🇷 | 13 |
| Tony Bettenhausen 🇺🇸 | 13 |
| Jack Brabham 🇦🇺 | 12 |
| Jim Rathmann 🇺🇸 | 12 |
| Rodger Ward 🇺🇸 | 12 |
| Andy Linden 🇺🇸 | 11 |
| Bruce McLaren 🇳🇿 | 11 |
| Derek Daly 🇮🇪 | 11 |
| Fernando Alonso 🇪🇸 | 11 |
| Jo Bonnier 🇸🇪 | 11 |
| John Surtees 🇬🇧 | 11 |
| Kimi Räikkönen 🇫🇮 | 11 |
| Marc Surer 🇨🇭 | 11 |
| Patrick Depailler 🇫🇷 | 11 |
| Ronnie Peterson 🇸🇪 | 11 |
| Bruno Giacomelli 🇮🇹 | 10 |
| Didier Pironi 🇫🇷 | 10 |
| Duane Carter 🇺🇸 | 10 |
| Hans-Joachim Stuck 🇩🇪 | 10 |
| Jacky Ickx 🇧🇪 | 10 |
| James Hunt 🇬🇧 | 10 |
| Johnnie Parsons 🇺🇸 | 10 |
| Thierry Boutsen 🇧🇪 | 10 |
| Ayrton Senna 🇧🇷 | 9 |
| Chris Amon 🇳🇿 | 9 |
| Dan Gurney 🇺🇸 | 9 |
| Denny Hulme 🇳🇿 | 9 |
| Eddie Johnson 🇺🇸 | 9 |
| Felipe Massa 🇧🇷 | 9 |
| Gene Hartley 🇺🇸 | 9 |
| Gilles Villeneuve 🇨🇦 | 9 |
| Jackie Stewart 🇬🇧 | 9 |
| Jimmy Bryan 🇺🇸 | 9 |
| Jo Siffert 🇨🇭 | 9 |
| Johnny Thomson 🇺🇸 | 9 |
| Paul Russo 🇺🇸 | 9 |
| Piercarlo Ghinzani 🇮🇹 | 9 |
| Sam Hanks 🇺🇸 | 9 |
| Arturo Merzario 🇮🇹 | 8 |
| David Coulthard 🇬🇧 | 8 |
| Don Freeland 🇺🇸 | 8 |
| Fred Agabashian 🇺🇸 | 8 |
| Giancarlo Fisichella 🇮🇹 | 8 |
| Innes Ireland 🇬🇧 | 8 |
| Jarno Trulli 🇮🇹 | 8 |
| Jean-Pierre Beltoise 🇫🇷 | 8 |
| Jim Clark 🇬🇧 | 8 |
| Manfred Winkelhock 🇩🇪 | 8 |
| Mark Webber 🇦🇺 | 8 |
| Michael Schumacher 🇩🇪 | 8 |
| Nick Heidfeld 🇩🇪 | 8 |
| Rubens Barrichello 🇧🇷 | 8 |
| Vittorio Brambilla 🇮🇹 | 8 |
| Brett Lunger 🇺🇸 | 7 |
| Chuck Stevenson 🇺🇸 | 7 |
| Gerhard Berger 🇦🇹 | 7 |
| Hector Rebaque 🇲🇽 | 7 |
| Jimmy Daywalt 🇺🇸 | 7 |
| Martin Brundle 🇬🇧 | 7 |
| Nico Rosberg 🇩🇪 | 7 |
| Ralf Schumacher 🇩🇪 | 7 |
| Stefan Johansson 🇸🇪 | 7 |
| Troy Ruttman 🇺🇸 | 7 |
| Brian Henton 🇬🇧 | 6 |
| Carlos Pace 🇧🇷 | 6 |
| Eliseo Salazar 🇨🇱 | 6 |
| Jack McGrath 🇺🇸 | 6 |
| Jacques Villeneuve 🇨🇦 | 6 |
| Jan Lammers 🇳🇱 | 6 |
| Jean-Pierre Jabouille 🇫🇷 | 6 |
| Jimmy Davies 🇺🇸 | 6 |
| Jimmy Reece 🇺🇸 | 6 |
| Johnny Boyd 🇺🇸 | 6 |
| Jonathan Palmer 🇬🇧 | 6 |
| Juan Pablo Montoya 🇨🇴 | 6 |
| Lewis Hamilton 🇬🇧 | 6 |
| Pat Flaherty 🇺🇸 | 6 |
| Pedro Rodríguez 🇲🇽 | 6 |
| Philippe Alliot 🇫🇷 | 6 |
| Sebastian Vettel 🇩🇪 | 6 |
| Teo Fabi 🇮🇹 | 6 |
| Al Herman 🇺🇸 | 5 |
| Al Keller 🇺🇸 | 5 |
| Alessandro Nannini 🇮🇹 | 5 |
| Bill Vukovich 🇺🇸 | 5 |
| Bob Christie 🇺🇸 | 5 |
| Bob Scott 🇺🇸 | 5 |
| Bob Sweikert 🇺🇸 | 5 |
| Bob Veith 🇺🇸 | 5 |
| Chico Serra 🇧🇷 | 5 |
| Daniel Ricciardo 🇦🇺 | 5 |
| Dick Rathmann 🇺🇸 | 5 |
| Ed Elisian 🇺🇸 | 5 |
| Ivan Capelli 🇮🇹 | 5 |
| Jerry Hoyt 🇺🇸 | 5 |
| Jochen Rindt 🇦🇹 | 5 |
| Mauro Baldi 🇮🇹 | 5 |
| Nico Hülkenberg 🇩🇪 | 5 |
| Pat O'Connor 🇺🇸 | 5 |
| Pierluigi Martini 🇮🇹 | 5 |
| Raul Boesel 🇧🇷 | 5 |
| Richie Ginther 🇺🇸 | 5 |
| Roberto Guerrero 🇨🇴 | 5 |
| Romain Grosjean 🇫🇷 | 5 |
| Satoru Nakajima 🇯🇵 | 5 |
| Sergio Pérez 🇲🇽 | 5 |
| Takuma Sato 🇯🇵 | 5 |
| Walt Faulkner 🇺🇸 | 5 |
| Alex Caffi 🇮🇹 | 4 |
| Alex Ribeiro 🇧🇷 | 4 |
| Art Cross 🇺🇸 | 4 |
| Chuck Weyant 🇺🇸 | 4 |
| Duke Dinsmore 🇺🇸 | 4 |
| Eddie Russo 🇺🇸 | 4 |
| Eddie Sachs 🇺🇸 | 4 |
| François Cevert 🇫🇷 | 4 |
| Gabriele Tarquini 🇮🇹 | 4 |
| Gunnar Nilsson 🇸🇪 | 4 |
| Hap Sharp 🇺🇸 | 4 |
| Heinz-Harald Frentzen 🇩🇪 | 4 |
| Henri Pescarolo 🇫🇷 | 4 |
| Jack Turner 🇺🇸 | 4 |
| Jackie Oliver 🇬🇧 | 4 |
| Jean Alesi 🇫🇷 | 4 |
| Jim Hall 🇺🇸 | 4 |
| Johnny Cecotto 🇻🇪 | 4 |
| Lorenzo Bandini 🇮🇹 | 4 |
| Manny Ayulo 🇺🇸 | 4 |
| Marshall Teague 🇺🇸 | 4 |
| Maurício Gugelmin 🇧🇷 | 4 |
| Mike Hailwood 🇬🇧 | 4 |
| Mike Spence 🇬🇧 | 4 |
| Nicola Larini 🇮🇹 | 4 |
| Olivier Panis 🇫🇷 | 4 |
| Pastor Maldonado 🇻🇪 | 4 |
| Pedro de la Rosa 🇪🇸 | 4 |
| Pete Lovely 🇺🇸 | 4 |
| Phil Hill 🇺🇸 | 4 |
| Rolf Stommelen 🇩🇪 | 4 |
| Roy Salvadori 🇬🇧 | 4 |
| Rupert Keegan 🇬🇧 | 4 |
| Stefano Modena 🇮🇹 | 4 |
| Tim Schenken 🇦🇺 | 4 |
| Tom Pryce 🇬🇧 | 4 |
| Travis Webb 🇺🇸 | 4 |
| Valtteri Bottas 🇫🇮 | 4 |
| Adrian Sutil 🇩🇪 | 3 |
| Aguri Suzuki 🇯🇵 | 3 |
| Andrea de Adamich 🇮🇹 | 3 |
| Anthony Foyt 🇺🇸 | 3 |
| Beppe Gabbiani 🇮🇹 | 3 |
| Bernd Schneider 🇩🇪 | 3 |
| Bertrand Gachot 🇧🇪 | 3 |
| Bill Cheesbourg 🇺🇸 | 3 |
| Bill Homeier 🇺🇸 | 3 |
| Bill Schindler 🇺🇸 | 3 |
| Cal Niday 🇺🇸 | 3 |
| Christian Danner 🇩🇪 | 3 |
| Christian Klien 🇦🇹 | 3 |
| Christijan Albers 🇳🇱 | 3 |
| Cliff Griffith 🇺🇸 | 3 |
| Corrado Fabi 🇮🇹 | 3 |
| Daniil Kvyat 🇷🇺 | 3 |
| Derek Bell 🇬🇧 | 3 |
| Duke Nalon 🇺🇸 | 3 |
| Eddie Irvine 🇬🇧 | 3 |
| Esteban Gutiérrez 🇲🇽 | 3 |
| George Connor 🇺🇸 | 3 |
| George Fonder 🇺🇸 | 3 |
| Heikki Kovalainen 🇫🇮 | 3 |
| Henry Banks 🇺🇸 | 3 |
| Howden Ganley 🇳🇿 | 3 |
| Huub Rothengatter 🇳🇱 | 3 |
| Jean-Éric Vergne 🇫🇷 | 3 |
| Johnnie Tolan 🇺🇸 | 3 |
| Johnny McDowell 🇺🇸 | 3 |
| Jos Verstappen 🇳🇱 | 3 |
| Len Sutton 🇺🇸 | 3 |
| Masten Gregory 🇺🇸 | 3 |
| Maurice Trintignant 🇫🇷 | 3 |
| Mika Häkkinen 🇫🇮 | 3 |
| Mike Magill 🇺🇸 | 3 |
| Mike Nazaruk 🇺🇸 | 3 |
| Olivier Grouillard 🇫🇷 | 3 |
| Paul Goldsmith 🇺🇸 | 3 |
| Peter Gethin 🇬🇧 | 3 |
| Peter Revson 🇺🇸 | 3 |
| Philippe Streiff 🇫🇷 | 3 |
| Ray Crawford 🇺🇸 | 3 |
| Reine Wisell 🇸🇪 | 3 |
| Roberto Moreno 🇧🇷 | 3 |
| Ronnie Bucknum 🇺🇸 | 3 |
| Shorty Templeman 🇺🇸 | 3 |
| Stefan Bellof 🇩🇪 | 3 |
| Stirling Moss 🇬🇧 | 3 |
| Tony Brooks 🇬🇧 | 3 |
| Trevor Taylor 🇬🇧 | 3 |
| Walt Hansgen 🇺🇸 | 3 |
| Wilson Fittipaldi 🇧🇷 | 3 |
| Yannick Dalmas 🇫🇷 | 3 |
| Alex Yoong 🇲🇾 | 2 |
| Alexander Wurz 🇦🇹 | 2 |
| Bill Holland 🇺🇸 | 2 |
| Billy Garrett 🇺🇸 | 2 |
| Bob Bondurant 🇺🇸 | 2 |
| Bobby Ball 🇺🇸 | 2 |
| Bobby Grim 🇺🇸 | 2 |
| Brian Redman 🇬🇧 | 2 |
| Carel Godin de Beaufort 🇳🇱 | 2 |
| Carl Scarborough 🇺🇸 | 2 |
| Carlos Sainz 🇪🇸 | 2 |
| Cecil Green 🇺🇸 | 2 |
| Charles Pic 🇫🇷 | 2 |
| Chet Miller 🇺🇸 | 2 |
| Cristiano da Matta 🇧🇷 | 2 |
| Danny Ongais 🇺🇸 | 2 |
| Danny Sullivan 🇺🇸 | 2 |
| Dempsey Wilson 🇺🇸 | 2 |
| Don Branson 🇺🇸 | 2 |
| Éric Bernard 🇫🇷 | 2 |
| Ernie McCoy 🇺🇸 | 2 |
| Felipe Nasr 🇧🇷 | 2 |
| François Hesnault 🇫🇷 | 2 |
| Gene Force 🇺🇸 | 2 |
| Geoff Lees 🇬🇧 | 2 |
| George Eaton 🇨🇦 | 2 |
| Gianni Morbidelli 🇮🇹 | 2 |
| Gregor Foitek 🇨🇭 | 2 |
| Hans Binder 🇦🇹 | 2 |
| Harald Ertl 🇦🇹 | 2 |
| Ian Ashley 🇬🇧 | 2 |
| Jackie Holmes 🇺🇸 | 2 |
| Jim McWithey 🇺🇸 | 2 |
| Jimmy Jackson 🇺🇸 | 2 |
| Joe James 🇺🇸 | 2 |
| Johnny Herbert 🇬🇧 | 2 |
| Jud Larson 🇺🇸 | 2 |
| Julian Bailey 🇬🇧 | 2 |
| Jyrki Järvilehto 🇫🇮 | 2 |
| Keith Andrews 🇺🇸 | 2 |
| Kevin Magnussen 🇩🇰 | 2 |
| Lee Wallard 🇺🇸 | 2 |
| Lloyd Ruby 🇺🇸 | 2 |
| Luis Pérez-Sala 🇪🇸 | 2 |
| Mack Hellings 🇺🇸 | 2 |
| Marcus Ericsson 🇸🇪 | 2 |
| Mauri Rose 🇺🇸 | 2 |
| Max Verstappen 🇳🇱 | 2 |
| Michel Leclère 🇫🇷 | 2 |
| Mika Salo 🇫🇮 | 2 |
| Mike Beuttler 🇬🇧 | 2 |
| Moisés Solana 🇲🇽 | 2 |
| Narain Karthikeyan 🇮🇳 | 2 |
| Olivier Gendebien 🇧🇪 | 2 |
| Paul di Resta 🇬🇧 | 2 |
| Piers Courage 🇬🇧 | 2 |
| Red Amick 🇺🇸 | 2 |
| Ricardo Zonta 🇧🇷 | 2 |
| Ricardo Zunino 🇦🇷 | 2 |
| Riccardo Paletti 🇮🇹 | 2 |
| Roger Penske 🇺🇸 | 2 |
| Sam Posey 🇺🇸 | 2 |
| Scott Speed 🇺🇸 | 2 |
| Skip Barber 🇺🇸 | 2 |
| Slim Borgudd 🇸🇪 | 2 |
| Tiago Monteiro 🇵🇹 | 2 |
| Tony Maggs 🇿🇦 | 2 |
| Vitantonio Liuzzi 🇮🇹 | 2 |
| Walt Brown 🇺🇸 | 2 |
| Wolfgang von Trips 🇩🇪 | 2 |
| Adrián Campos 🇪🇸 | 1 |
| Alan Stacey 🇬🇧 | 1 |
| Alberto Ascari 🇮🇹 | 1 |
| Alessandro de Tomaso 🇦🇷 | 1 |
| Alexander Rossi 🇺🇸 | 1 |
| Allan McNish 🇬🇧 | 1 |
| Allen Berg 🇨🇦 | 1 |
| Anthony Davidson 🇬🇧 | 1 |
| Art Bisch 🇺🇸 | 1 |
| Bayliss Levrett 🇺🇸 | 1 |
| Bill Cantrell 🇺🇸 | 1 |
| Bill Mackey 🇺🇸 | 1 |
| Bob Drake 🇺🇸 | 1 |
| Bob Evans 🇬🇧 | 1 |
| Bob Said 🇺🇸 | 1 |
| Bobby Rahal 🇺🇸 | 1 |
| Bobby Unser 🇺🇸 | 1 |
| Brian Naylor 🇬🇧 | 1 |
| Bruno Senna 🇧🇷 | 1 |
| Bud Tingelstad 🇺🇸 | 1 |
| Carl Forberg 🇺🇸 | 1 |
| Chris Craft 🇬🇧 | 1 |
| Chris Irwin 🇬🇧 | 1 |
| Chuck Arnold 🇺🇸 | 1 |
| Chuck Daigh 🇺🇸 | 1 |
| Claudio Langes 🇮🇹 | 1 |
| Cliff Allison 🇬🇧 | 1 |
| Danny Kladis 🇺🇸 | 1 |
| Dave Kennedy 🇮🇪 | 1 |
| David Hobbs 🇬🇧 | 1 |
| David Walker 🇦🇺 | 1 |
| Don Edmunds 🇺🇸 | 1 |
| Elmer George 🇺🇸 | 1 |
| Emanuele Pirro 🇮🇹 | 1 |
| Emilio de Villota 🇪🇸 | 1 |
| Enrique Bernoldi 🇧🇷 | 1 |
| Eric van de Poele 🇧🇪 | 1 |
| Érik Comas 🇫🇷 | 1 |
| Ernie de Vos 🇳🇱 | 1 |
| Esteban Ocon 🇫🇷 | 1 |
| Franck Montagny 🇫🇷 | 1 |
| Frank Armi 🇺🇸 | 1 |
| Fritz d'Orey 🇧🇷 | 1 |
| Gary Brabham 🇦🇺 | 1 |
| Gastón Mazzacane 🇦🇷 | 1 |
| George Amick 🇺🇸 | 1 |
| George Constantine 🇺🇸 | 1 |
| George Follmer 🇺🇸 | 1 |
| Giancarlo Baghetti 🇮🇹 | 1 |
| Gianmaria Bruni 🇮🇹 | 1 |
| Giedo van der Garde 🇳🇱 | 1 |
| Giorgio Pantano 🇮🇹 | 1 |
| Gus Hutchison 🇺🇸 | 1 |
| Guy Ligier 🇫🇷 | 1 |
| Harry Blanchard 🇺🇸 | 1 |
| Harry Schell 🇺🇸 | 1 |
| Helmut Marko 🇦🇹 | 1 |
| Helmuth Koinigg 🇦🇹 | 1 |
| Henry Taylor 🇬🇧 | 1 |
| Ian Burgess 🇬🇧 | 1 |
| Ian Scheckter 🇿🇦 | 1 |
| Ingo Hoffmann 🇧🇷 | 1 |
| Jacques Villeneuve Sr. 🇨🇦 | 1 |
| Jerry Unser 🇺🇸 | 1 |
| Jim Hurtubise 🇺🇸 | 1 |
| Jim Rigsby 🇺🇸 | 1 |
| Joachim Winkelhock 🇩🇪 | 1 |
| John Cannon 🇨🇦 | 1 |
| Johnny Dumfries 🇬🇧 | 1 |
| Johnny Mantz 🇺🇸 | 1 |
| Johnny Servoz-Gavin 🇫🇷 | 1 |
| Joie Chitwood 🇺🇸 | 1 |
| Jolyon Palmer 🇬🇧 | 1 |
| José Dolhem 🇫🇷 | 1 |
| Jules Bianchi 🇫🇷 | 1 |
| Justin Wilson 🇬🇧 | 1 |
| Kamui Kobayashi 🇯🇵 | 1 |
| Ken Miles 🇬🇧 | 1 |
| Kevin Cogan 🇺🇸 | 1 |
| Lamberto Leoni 🇮🇹 | 1 |
| Larry Crockett 🇺🇸 | 1 |
| Larry Perkins 🇦🇺 | 1 |
| Lella Lombardi 🇮🇹 | 1 |
| Len Duncan 🇺🇸 | 1 |
| Lucien Bianchi 🇧🇪 | 1 |
| Marc Gené 🇪🇸 | 1 |
| Mark Blundell 🇬🇧 | 1 |
| Mark Donohue 🇺🇸 | 1 |
| Martin Donnelly 🇬🇧 | 1 |
| Max Chilton 🇬🇧 | 1 |
| Michael Bleekemolen 🇳🇱 | 1 |
| Miguel Ángel Guerra 🇦🇷 | 1 |
| Mike Thackwell 🇳🇿 | 1 |
| Mike Wilds 🇬🇧 | 1 |
| Myron Fohr 🇺🇸 | 1 |
| Nanni Galli 🇮🇹 | 1 |
| Nicolas Kiesa 🇩🇰 | 1 |
| Oscar Larrauri 🇦🇷 | 1 |
| Otto Stuppacher 🇦🇹 | 1 |
| Paolo Barilla 🇮🇹 | 1 |
| Pascal Fabre 🇫🇷 | 1 |
| Pascal Wehrlein 🇩🇪 | 1 |
| Patrick Friesacher 🇦🇹 | 1 |
| Patrick Nève 🇧🇪 | 1 |
| Pedro Chaves 🇵🇹 | 1 |
| Pedro Diniz 🇧🇷 | 1 |
| Peter Arundell 🇬🇧 | 1 |
| Peter Broeker 🇨🇦 | 1 |
| Peter Ryan 🇨🇦 | 1 |
| Peter Westbury 🇬🇧 | 1 |
| Phil Cade 🇺🇸 | 1 |
| Pierre-Henri Raphanel 🇫🇷 | 1 |
| Ralph Firman 🇮🇪 | 1 |
| Renzo Zorzi 🇮🇹 | 1 |
| Richard Attwood 🇬🇧 | 1 |
| Rikky von Opel 🇱🇮 | 1 |
| Rob Schroeder 🇬🇧 | 1 |
| Roelof Wunderink 🇳🇱 | 1 |
| Ron Flockhart 🇬🇧 | 1 |
| Siegfried Stohr 🇮🇹 | 1 |
| Silvio Moser 🇨🇭 | 1 |
| Stephen South 🇬🇧 | 1 |
| Timmy Mayer 🇺🇸 | 1 |
| Timo Glock 🇩🇪 | 1 |
| Tomáš Enge 🇨🇿 | 1 |
| Tommy Byrne 🇮🇪 | 1 |
| Tony Brise 🇬🇧 | 1 |
| Vic Elford 🇬🇧 | 1 |
| Vitaly Petrov 🇷🇺 | 1 |
| Volker Weidler 🇩🇪 | 1 |
| Walt Ader 🇺🇸 | 1 |
| Warwick Brown 🇦🇺 | 1 |
| Wayne Weiler 🇺🇸 | 1 |
| Will Stevens 🇬🇧 | 1 |
| Zsolt Baumgartner 🇭🇺 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 429 |
| **Total Sum** | 1809.000 |
| **Mean μ (Average)** | 4.217 |
| **Maximum** | 23.000 |
| **75th Percentile** | 5.000 |
| **Median** | 3.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 17.457 |
| **Standard Deviation σ** | 4.178 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
