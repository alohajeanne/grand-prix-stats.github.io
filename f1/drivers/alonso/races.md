---
title: List of Formula 1® Races by Fernando Alonso
layout: page
collectionName: drivers
collectionId: alonso
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

| Season | Round | Name | Date | Grid | Final Position | Laps Completed | Time | Winning Driver | Winning Constructor |
|--|--|--|--|--|--|--|--|--|--|
| 2016 | 21 | 2016 Abu Dhabi Grand Prix 🇦🇪 | 2016-11-27 | 9 | 10 | 55 | +59.896 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 20 | 2016 Brazilian Grand Prix 🇧🇷 | 2016-11-13 | 10 | 10 | 71 | +44.432 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 19 | 2016 Mexican Grand Prix 🇲🇽 | 2016-10-30 | 11 | 13 | 70 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 18 | 2016 United States Grand Prix 🇺🇸 | 2016-10-23 | 12 | 5 | 56 | +1:33.953 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 17 | 2016 Japanese Grand Prix 🇯🇵 | 2016-10-09 | 15 | 16 | 52 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2016 | 16 | 2016 Malaysian Grand Prix 🇲🇾 | 2016-10-02 | 22 | 7 | 56 | +1:05.205 | Daniel Ricciardo 🇦🇺 | Red Bull 🇦🇹 |
| 2016 | 15 | 2016 Singapore Grand Prix 🇸🇬 | 2016-09-18 | 9 | 7 | 61 | +1:29.198 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2016 | 14 | 2016 Italian Grand Prix 🇮🇹 | 2016-09-04 | 12 | 14 | 52 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2016 | 13 | 2016 Belgian Grand Prix 🇧🇪 | 2016-08-28 | 22 | 7 | 44 | +59.445 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2016 | 12 | 2016 German Grand Prix 🇩🇪 | 2016-07-31 | 13 | 12 | 66 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 11 | 2016 Hungarian Grand Prix 🇭🇺 | 2016-07-24 | 7 | 7 | 69 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 10 | 2016 British Grand Prix 🇬🇧 | 2016-07-10 | 9 | 13 | 51 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 9 | 2016 Austrian Grand Prix 🇦🇹 | 2016-07-03 | 14 | 18 | 64 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 8 | 2016 European Grand Prix 🇦🇿 | 2016-06-19 | 13 | R | 42 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2016 | 7 | 2016 Canadian Grand Prix 🇨🇦 | 2016-06-12 | 10 | 11 | 69 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 6 | 2016 Monaco Grand Prix 🇲🇨 | 2016-05-29 | 9 | 5 | 78 | +1:25.076 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2016 | 5 | 2016 Spanish Grand Prix 🇪🇸 | 2016-05-15 | 10 | R | 45 |   | Max Verstappen 🇳🇱 | Red Bull 🇦🇹 |
| 2016 | 4 | 2016 Russian Grand Prix 🇷🇺 | 2016-05-01 | 14 | 6 | 52 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2016 | 3 | 2016 Chinese Grand Prix 🇨🇳 | 2016-04-17 | 11 | 12 | 56 | +1:37.253 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2016 | 1 | 2016 Australian Grand Prix 🇦🇺 | 2016-03-20 | 11 | R | 16 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2015 | 19 | 2015 Abu Dhabi Grand Prix 🇦🇪 | 2015-11-29 | 16 | 17 | 53 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2015 | 18 | 2015 Brazilian Grand Prix 🇧🇷 | 2015-11-15 | 20 | 15 | 70 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2015 | 17 | 2015 Mexican Grand Prix 🇲🇽 | 2015-11-01 | 18 | R | 1 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2015 | 16 | 2015 United States Grand Prix 🇺🇸 | 2015-10-25 | 9 | 11 | 56 | +54.816 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 15 | 2015 Russian Grand Prix 🇷🇺 | 2015-10-11 | 19 | 11 | 53 | +1:31.210 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 14 | 2015 Japanese Grand Prix 🇯🇵 | 2015-09-27 | 12 | 11 | 52 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 13 | 2015 Singapore Grand Prix 🇸🇬 | 2015-09-20 | 12 | R | 33 |   | Sebastian Vettel 🇩🇪 | Ferrari 🇮🇹 |
| 2015 | 12 | 2015 Italian Grand Prix 🇮🇹 | 2015-09-06 | 16 | 18 | 47 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 11 | 2015 Belgian Grand Prix 🇧🇪 | 2015-08-23 | 20 | 13 | 42 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 10 | 2015 Hungarian Grand Prix 🇭🇺 | 2015-07-26 | 15 | 5 | 69 | +49.079 | Sebastian Vettel 🇩🇪 | Ferrari 🇮🇹 |
| 2015 | 9 | 2015 British Grand Prix 🇬🇧 | 2015-07-05 | 17 | 10 | 51 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 8 | 2015 Austrian Grand Prix 🇦🇹 | 2015-06-21 | 19 | R | 0 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2015 | 7 | 2015 Canadian Grand Prix 🇨🇦 | 2015-06-07 | 13 | R | 44 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 6 | 2015 Monaco Grand Prix 🇲🇨 | 2015-05-24 | 13 | R | 41 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2015 | 5 | 2015 Spanish Grand Prix 🇪🇸 | 2015-05-10 | 13 | R | 26 |   | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2015 | 4 | 2015 Bahrain Grand Prix 🇧🇭 | 2015-04-19 | 14 | 11 | 56 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 3 | 2015 Chinese Grand Prix 🇨🇳 | 2015-04-12 | 18 | 12 | 55 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2015 | 2 | 2015 Malaysian Grand Prix 🇲🇾 | 2015-03-29 | 18 | R | 21 |   | Sebastian Vettel 🇩🇪 | Ferrari 🇮🇹 |
| 2014 | 19 | 2014 Abu Dhabi Grand Prix 🇦🇪 | 2014-11-23 | 8 | 9 | 55 | +1:25.813 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 18 | 2014 Brazilian Grand Prix 🇧🇷 | 2014-11-09 | 8 | 6 | 71 | +1:01.906 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2014 | 17 | 2014 United States Grand Prix 🇺🇸 | 2014-11-02 | 6 | 6 | 56 | +1:35.231 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 16 | 2014 Russian Grand Prix 🇷🇺 | 2014-10-12 | 7 | 6 | 53 | +1:00.016 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 15 | 2014 Japanese Grand Prix 🇯🇵 | 2014-10-05 | 5 | R | 2 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 14 | 2014 Singapore Grand Prix 🇸🇬 | 2014-09-21 | 5 | 4 | 60 | +15.389 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 13 | 2014 Italian Grand Prix 🇮🇹 | 2014-09-07 | 7 | R | 28 |   | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 12 | 2014 Belgian Grand Prix 🇧🇪 | 2014-08-24 | 4 | 7 | 44 | +1:01.162 | Daniel Ricciardo 🇦🇺 | Red Bull 🇦🇹 |
| 2014 | 11 | 2014 Hungarian Grand Prix 🇭🇺 | 2014-07-27 | 5 | 2 | 70 | +5.225 | Daniel Ricciardo 🇦🇺 | Red Bull 🇦🇹 |
| 2014 | 10 | 2014 German Grand Prix 🇩🇪 | 2014-07-20 | 7 | 5 | 67 | +52.467 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2014 | 9 | 2014 British Grand Prix 🇬🇧 | 2014-07-06 | 16 | 6 | 52 | +59.946 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 8 | 2014 Austrian Grand Prix 🇦🇹 | 2014-06-22 | 4 | 5 | 71 | +18.553 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2014 | 7 | 2014 Canadian Grand Prix 🇨🇦 | 2014-06-08 | 7 | 6 | 70 | +14.869 | Daniel Ricciardo 🇦🇺 | Red Bull 🇦🇹 |
| 2014 | 6 | 2014 Monaco Grand Prix 🇲🇨 | 2014-05-25 | 5 | 4 | 78 | +32.452 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2014 | 5 | 2014 Spanish Grand Prix 🇪🇸 | 2014-05-11 | 7 | 6 | 66 | +1:27.743 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 4 | 2014 Chinese Grand Prix 🇨🇳 | 2014-04-20 | 5 | 3 | 54 | +23.604 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 3 | 2014 Bahrain Grand Prix 🇧🇭 | 2014-04-06 | 9 | 9 | 57 | +32.595 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 2 | 2014 Malaysian Grand Prix 🇲🇾 | 2014-03-30 | 4 | 4 | 56 | +35.992 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2014 | 1 | 2014 Australian Grand Prix 🇦🇺 | 2014-03-16 | 5 | 4 | 57 | +35.284 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2013 | 19 | 2013 Brazilian Grand Prix 🇧🇷 | 2013-11-24 | 3 | 3 | 71 | +18.913 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 18 | 2013 United States Grand Prix 🇺🇸 | 2013-11-17 | 6 | 5 | 56 | +29.592 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 17 | 2013 Abu Dhabi Grand Prix 🇦🇪 | 2013-11-03 | 10 | 5 | 55 | +1:07.181 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 16 | 2013 Indian Grand Prix 🇮🇳 | 2013-10-27 | 8 | 11 | 60 | +1:18.297 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 15 | 2013 Japanese Grand Prix 🇯🇵 | 2013-10-13 | 8 | 4 | 53 | +45.605 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 14 | 2013 Korean Grand Prix 🇰🇷 | 2013-10-06 | 5 | 6 | 55 | +26.189 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 13 | 2013 Singapore Grand Prix 🇸🇬 | 2013-09-22 | 7 | 2 | 61 | +32.627 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 12 | 2013 Italian Grand Prix 🇮🇹 | 2013-09-08 | 5 | 2 | 53 | +5.467 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 11 | 2013 Belgian Grand Prix 🇧🇪 | 2013-08-25 | 9 | 2 | 44 | +16.869 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 10 | 2013 Hungarian Grand Prix 🇭🇺 | 2013-07-28 | 5 | 5 | 70 | +31.411 | Lewis Hamilton 🇬🇧 | Mercedes 🇩🇪 |
| 2013 | 9 | 2013 German Grand Prix 🇩🇪 | 2013-07-07 | 8 | 4 | 60 | +7.721 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 8 | 2013 British Grand Prix 🇬🇧 | 2013-06-30 | 9 | 3 | 52 | +7.124 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2013 | 7 | 2013 Canadian Grand Prix 🇨🇦 | 2013-06-09 | 6 | 2 | 70 | +14.408 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 6 | 2013 Monaco Grand Prix 🇲🇨 | 2013-05-26 | 6 | 7 | 78 | +26.734 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2013 | 5 | 2013 Spanish Grand Prix 🇪🇸 | 2013-05-12 | 5 | 1 | 66 | 1:39:16.596 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2013 | 4 | 2013 Bahrain Grand Prix 🇧🇭 | 2013-04-21 | 3 | 8 | 57 | +37.574 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 3 | 2013 Chinese Grand Prix 🇨🇳 | 2013-04-14 | 3 | 1 | 56 | 1:36:26.945 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2013 | 2 | 2013 Malaysian Grand Prix 🇲🇾 | 2013-03-24 | 3 | R | 1 |   | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2013 | 1 | 2013 Australian Grand Prix 🇦🇺 | 2013-03-17 | 5 | 2 | 58 | +12.451 | Kimi Räikkönen 🇫🇮 | Lotus F1 🇬🇧 |
| 2012 | 20 | 2012 Brazilian Grand Prix 🇧🇷 | 2012-11-25 | 7 | 2 | 71 | +2.754 | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2012 | 19 | 2012 United States Grand Prix 🇺🇸 | 2012-11-18 | 7 | 3 | 56 | +39.229 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2012 | 18 | 2012 Abu Dhabi Grand Prix 🇦🇪 | 2012-11-04 | 6 | 2 | 55 | +0.852 | Kimi Räikkönen 🇫🇮 | Lotus F1 🇬🇧 |
| 2012 | 17 | 2012 Indian Grand Prix 🇮🇳 | 2012-10-28 | 5 | 2 | 60 | +9.437 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2012 | 16 | 2012 Korean Grand Prix 🇰🇷 | 2012-10-14 | 4 | 3 | 55 | +13.944 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2012 | 15 | 2012 Japanese Grand Prix 🇯🇵 | 2012-10-07 | 6 | R | 0 |   | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2012 | 14 | 2012 Singapore Grand Prix 🇸🇬 | 2012-09-23 | 5 | 3 | 59 | +15.227 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2012 | 13 | 2012 Italian Grand Prix 🇮🇹 | 2012-09-09 | 10 | 3 | 53 | +20.594 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2012 | 12 | 2012 Belgian Grand Prix 🇧🇪 | 2012-09-02 | 5 | R | 0 |   | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2012 | 11 | 2012 Hungarian Grand Prix 🇭🇺 | 2012-07-29 | 6 | 5 | 69 | +26.653 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2012 | 10 | 2012 German Grand Prix 🇩🇪 | 2012-07-22 | 1 | 1 | 67 | 1:31:05.862 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2012 | 9 | 2012 British Grand Prix 🇬🇧 | 2012-07-08 | 1 | 2 | 52 | +3.060 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2012 | 8 | 2012 European Grand Prix 🇪🇸 | 2012-06-24 | 11 | 1 | 57 | 1:44:16.649 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2012 | 7 | 2012 Canadian Grand Prix 🇨🇦 | 2012-06-10 | 3 | 5 | 70 | +13.411 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2012 | 6 | 2012 Monaco Grand Prix 🇲🇨 | 2012-05-27 | 5 | 3 | 78 | +0.947 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2012 | 5 | 2012 Spanish Grand Prix 🇪🇸 | 2012-05-13 | 2 | 2 | 66 | +3.195 | Pastor Maldonado 🇻🇪 | Williams 🇬🇧 |
| 2012 | 4 | 2012 Bahrain Grand Prix 🇧🇭 | 2012-04-22 | 9 | 7 | 57 | +57.803 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2012 | 3 | 2012 Chinese Grand Prix 🇨🇳 | 2012-04-15 | 9 | 9 | 56 | +37.256 | Nico Rosberg 🇩🇪 | Mercedes 🇩🇪 |
| 2012 | 2 | 2012 Malaysian Grand Prix 🇲🇾 | 2012-03-25 | 8 | 1 | 56 | 2:44:51.812 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2012 | 1 | 2012 Australian Grand Prix 🇦🇺 | 2012-03-18 | 12 | 5 | 58 | +21.565 | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2011 | 19 | 2011 Brazilian Grand Prix 🇧🇷 | 2011-11-27 | 5 | 4 | 71 | +35.048 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2011 | 18 | 2011 Abu Dhabi Grand Prix 🇦🇪 | 2011-11-13 | 5 | 2 | 55 | +8.457 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2011 | 17 | 2011 Indian Grand Prix 🇮🇳 | 2011-10-30 | 3 | 3 | 60 | +24.301 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 16 | 2011 Korean Grand Prix 🇰🇷 | 2011-10-16 | 6 | 5 | 55 | +15.689 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 15 | 2011 Japanese Grand Prix 🇯🇵 | 2011-10-09 | 5 | 2 | 53 | +1.160 | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2011 | 14 | 2011 Singapore Grand Prix 🇸🇬 | 2011-09-25 | 5 | 4 | 61 | +55.449 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 13 | 2011 Italian Grand Prix 🇮🇹 | 2011-09-11 | 4 | 3 | 53 | +16.909 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 12 | 2011 Belgian Grand Prix 🇧🇪 | 2011-08-28 | 8 | 4 | 44 | +13.022 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 11 | 2011 Hungarian Grand Prix 🇭🇺 | 2011-07-31 | 5 | 3 | 70 | +19.819 | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2011 | 10 | 2011 German Grand Prix 🇩🇪 | 2011-07-24 | 4 | 2 | 60 | +3.980 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2011 | 9 | 2011 British Grand Prix 🇬🇧 | 2011-07-10 | 3 | 1 | 52 | 1:28:41.194 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2011 | 8 | 2011 European Grand Prix 🇪🇸 | 2011-06-26 | 4 | 2 | 57 | +10.891 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 7 | 2011 Canadian Grand Prix 🇨🇦 | 2011-06-12 | 2 | R | 36 |   | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2011 | 6 | 2011 Monaco Grand Prix 🇲🇨 | 2011-05-29 | 4 | 2 | 78 | +1.138 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 5 | 2011 Spanish Grand Prix 🇪🇸 | 2011-05-22 | 4 | 5 | 65 |   | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 4 | 2011 Turkish Grand Prix 🇹🇷 | 2011-05-08 | 5 | 3 | 58 | +10.075 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 3 | 2011 Chinese Grand Prix 🇨🇳 | 2011-04-17 | 5 | 7 | 56 | +30.622 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2011 | 2 | 2011 Malaysian Grand Prix 🇲🇾 | 2011-04-10 | 5 | 6 | 56 | +37.248 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2011 | 1 | 2011 Australian Grand Prix 🇦🇺 | 2011-03-27 | 5 | 4 | 58 | +31.772 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 19 | 2010 Abu Dhabi Grand Prix 🇦🇪 | 2010-11-14 | 3 | 7 | 55 | +43.797 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 18 | 2010 Brazilian Grand Prix 🇧🇷 | 2010-11-07 | 5 | 3 | 71 | +6.807 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 17 | 2010 Korean Grand Prix 🇰🇷 | 2010-10-24 | 3 | 1 | 55 | 2:48:20.810 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2010 | 16 | 2010 Japanese Grand Prix 🇯🇵 | 2010-10-10 | 4 | 3 | 53 | +2.721 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 15 | 2010 Singapore Grand Prix 🇸🇬 | 2010-09-26 | 1 | 1 | 61 | 1:57:53.579 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2010 | 14 | 2010 Italian Grand Prix 🇮🇹 | 2010-09-12 | 1 | 1 | 53 | 1:16:24.572 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2010 | 13 | 2010 Belgian Grand Prix 🇧🇪 | 2010-08-29 | 10 | R | 37 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 12 | 2010 Hungarian Grand Prix 🇭🇺 | 2010-08-01 | 3 | 2 | 70 | +17.821 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2010 | 11 | 2010 German Grand Prix 🇩🇪 | 2010-07-25 | 2 | 1 | 67 | 1:27.38.684 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2010 | 10 | 2010 British Grand Prix 🇬🇧 | 2010-07-11 | 3 | 14 | 52 | +1:02.385 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2010 | 9 | 2010 European Grand Prix 🇪🇸 | 2010-06-27 | 4 | 8 | 57 | +32.809 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 8 | 2010 Canadian Grand Prix 🇨🇦 | 2010-06-13 | 3 | 3 | 70 | +9.214 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 7 | 2010 Turkish Grand Prix 🇹🇷 | 2010-05-30 | 12 | 8 | 58 | +46.544 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 6 | 2010 Monaco Grand Prix 🇲🇨 | 2010-05-16 | 24 | 6 | 78 | +6.341 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2010 | 5 | 2010 Spanish Grand Prix 🇪🇸 | 2010-05-09 | 4 | 2 | 66 | +24.065 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2010 | 4 | 2010 Chinese Grand Prix 🇨🇳 | 2010-04-18 | 3 | 4 | 56 | +11.869 | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 3 | 2010 Malaysian Grand Prix 🇲🇾 | 2010-04-04 | 19 | 13 | 54 |   | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 2 | 2010 Australian Grand Prix 🇦🇺 | 2010-03-28 | 3 | 4 | 58 | +16.304 | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 1 | 2010 Bahrain Grand Prix 🇧🇭 | 2010-03-14 | 3 | 1 | 49 | 1:39:20.396 | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |
| 2009 | 17 | 2009 Abu Dhabi Grand Prix 🇦🇪 | 2009-11-01 | 15 | 14 | 55 | +1:09.687 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2009 | 16 | 2009 Brazilian Grand Prix 🇧🇷 | 2009-10-18 | 10 | R | 0 |   | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2009 | 15 | 2009 Japanese Grand Prix 🇯🇵 | 2009-10-04 | 16 | 10 | 53 | +13.065 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2009 | 14 | 2009 Singapore Grand Prix 🇸🇬 | 2009-09-27 | 5 | 3 | 61 | +16.624 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2009 | 13 | 2009 Italian Grand Prix 🇮🇹 | 2009-09-13 | 8 | 5 | 53 | +59.182 | Rubens Barrichello 🇧🇷 | Brawn 🇬🇧 |
| 2009 | 12 | 2009 Belgian Grand Prix 🇧🇪 | 2009-08-30 | 13 | R | 26 |   | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2009 | 11 | 2009 European Grand Prix 🇪🇸 | 2009-08-23 | 8 | 6 | 57 | +27.744 | Rubens Barrichello 🇧🇷 | Brawn 🇬🇧 |
| 2009 | 10 | 2009 Hungarian Grand Prix 🇭🇺 | 2009-07-26 | 1 | R | 15 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2009 | 9 | 2009 German Grand Prix 🇩🇪 | 2009-07-12 | 12 | 7 | 60 | +24.888 | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2009 | 8 | 2009 British Grand Prix 🇬🇧 | 2009-06-21 | 10 | 14 | 59 |   | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2009 | 7 | 2009 Turkish Grand Prix 🇹🇷 | 2009-06-07 | 8 | 10 | 58 | +1:02.420 | Jenson Button 🇬🇧 | Brawn 🇬🇧 |
| 2009 | 6 | 2009 Monaco Grand Prix 🇲🇨 | 2009-05-24 | 9 | 7 | 78 | +37.839 | Jenson Button 🇬🇧 | Brawn 🇬🇧 |
| 2009 | 5 | 2009 Spanish Grand Prix 🇪🇸 | 2009-05-10 | 8 | 5 | 66 | +43.166 | Jenson Button 🇬🇧 | Brawn 🇬🇧 |
| 2009 | 4 | 2009 Bahrain Grand Prix 🇧🇭 | 2009-04-26 | 7 | 8 | 57 | +52.775 | Jenson Button 🇬🇧 | Brawn 🇬🇧 |
| 2009 | 3 | 2009 Chinese Grand Prix 🇨🇳 | 2009-04-19 | 2 | 9 | 56 | +1:24.309 | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2009 | 2 | 2009 Malaysian Grand Prix 🇲🇾 | 2009-04-05 | 9 | 11 | 31 |   | Jenson Button 🇬🇧 | Brawn 🇬🇧 |
| 2009 | 1 | 2009 Australian Grand Prix 🇦🇺 | 2009-03-29 | 10 | 5 | 58 | +4.879 | Jenson Button 🇬🇧 | Brawn 🇬🇧 |
| 2008 | 18 | 2008 Brazilian Grand Prix 🇧🇷 | 2008-11-02 | 6 | 2 | 71 | +13.298 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2008 | 17 | 2008 Chinese Grand Prix 🇨🇳 | 2008-10-19 | 4 | 4 | 56 | +18.370 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2008 | 16 | 2008 Japanese Grand Prix 🇯🇵 | 2008-10-12 | 4 | 1 | 67 | 1:30:21.892 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2008 | 15 | 2008 Singapore Grand Prix 🇸🇬 | 2008-09-28 | 15 | 1 | 61 | 1:57:16.304 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2008 | 14 | 2008 Italian Grand Prix 🇮🇹 | 2008-09-14 | 8 | 4 | 53 | +23.903 | Sebastian Vettel 🇩🇪 | Toro Rosso 🇮🇹 |
| 2008 | 13 | 2008 Belgian Grand Prix 🇧🇪 | 2008-09-07 | 6 | 4 | 44 | +14.478 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2008 | 12 | 2008 European Grand Prix 🇪🇸 | 2008-08-24 | 12 | R | 0 |   | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2008 | 11 | 2008 Hungarian Grand Prix 🇭🇺 | 2008-08-03 | 7 | 4 | 70 | +21.614 | Heikki Kovalainen 🇫🇮 | McLaren 🇬🇧 |
| 2008 | 10 | 2008 German Grand Prix 🇩🇪 | 2008-07-20 | 5 | 11 | 67 | +38.600 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2008 | 9 | 2008 British Grand Prix 🇬🇧 | 2008-07-06 | 6 | 6 | 59 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2008 | 8 | 2008 French Grand Prix 🇫🇷 | 2008-06-22 | 3 | 8 | 70 | +43.372 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2008 | 7 | 2008 Canadian Grand Prix 🇨🇦 | 2008-06-08 | 4 | R | 44 |   | Robert Kubica 🇵🇱 | BMW Sauber 🇩🇪 |
| 2008 | 6 | 2008 Monaco Grand Prix 🇲🇨 | 2008-05-25 | 7 | 10 | 75 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2008 | 5 | 2008 Turkish Grand Prix 🇹🇷 | 2008-05-11 | 7 | 6 | 58 | +53.724 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2008 | 4 | 2008 Spanish Grand Prix 🇪🇸 | 2008-04-27 | 2 | R | 34 |   | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2008 | 3 | 2008 Bahrain Grand Prix 🇧🇭 | 2008-04-06 | 10 | 10 | 57 | +1:17.181 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2008 | 2 | 2008 Malaysian Grand Prix 🇲🇾 | 2008-03-23 | 7 | 8 | 56 | +1:10.041 | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2008 | 1 | 2008 Australian Grand Prix 🇦🇺 | 2008-03-16 | 11 | 4 | 58 | +17.181 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2007 | 17 | 2007 Brazilian Grand Prix 🇧🇷 | 2007-10-21 | 4 | 3 | 71 | +57.019 | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2007 | 16 | 2007 Chinese Grand Prix 🇨🇳 | 2007-10-07 | 4 | 2 | 56 | +9.806 | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2007 | 15 | 2007 Japanese Grand Prix 🇯🇵 | 2007-09-30 | 2 | R | 41 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2007 | 14 | 2007 Belgian Grand Prix 🇧🇪 | 2007-09-16 | 3 | 3 | 44 | +14.343 | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2007 | 13 | 2007 Italian Grand Prix 🇮🇹 | 2007-09-09 | 1 | 1 | 53 | 1:18:37.806 | Fernando Alonso 🇪🇸 | McLaren 🇬🇧 |
| 2007 | 12 | 2007 Turkish Grand Prix 🇹🇷 | 2007-08-26 | 4 | 3 | 58 | +26.181 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2007 | 11 | 2007 Hungarian Grand Prix 🇭🇺 | 2007-08-05 | 6 | 4 | 70 | +44.858 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2007 | 10 | 2007 European Grand Prix 🇩🇪 | 2007-07-22 | 2 | 1 | 60 | 2:06:26.358 | Fernando Alonso 🇪🇸 | McLaren 🇬🇧 |
| 2007 | 9 | 2007 British Grand Prix 🇬🇧 | 2007-07-08 | 3 | 2 | 59 | +2.459 | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2007 | 8 | 2007 French Grand Prix 🇫🇷 | 2007-07-01 | 10 | 7 | 70 | +56.516 | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2007 | 7 | 2007 United States Grand Prix 🇺🇸 | 2007-06-17 | 2 | 2 | 73 | +1.5 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2007 | 6 | 2007 Canadian Grand Prix 🇨🇦 | 2007-06-10 | 2 | 7 | 70 | +21.936 | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2007 | 5 | 2007 Monaco Grand Prix 🇲🇨 | 2007-05-27 | 1 | 1 | 78 | 1:40:29.329 | Fernando Alonso 🇪🇸 | McLaren 🇬🇧 |
| 2007 | 4 | 2007 Spanish Grand Prix 🇪🇸 | 2007-05-13 | 2 | 3 | 65 | +17.456 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2007 | 3 | 2007 Bahrain Grand Prix 🇧🇭 | 2007-04-15 | 4 | 5 | 57 | +14.426 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2007 | 2 | 2007 Malaysian Grand Prix 🇲🇾 | 2007-04-08 | 2 | 1 | 56 | 1:32:14.930 | Fernando Alonso 🇪🇸 | McLaren 🇬🇧 |
| 2007 | 1 | 2007 Australian Grand Prix 🇦🇺 | 2007-03-18 | 2 | 2 | 58 | +7.242 | Kimi Räikkönen 🇫🇮 | Ferrari 🇮🇹 |
| 2006 | 18 | 2006 Brazilian Grand Prix 🇧🇷 | 2006-10-22 | 4 | 2 | 71 | +18.658 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2006 | 17 | 2006 Japanese Grand Prix 🇯🇵 | 2006-10-08 | 5 | 1 | 53 | 1:23:52.413 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2006 | 16 | 2006 Chinese Grand Prix 🇨🇳 | 2006-10-01 | 1 | 2 | 56 | +3.121 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2006 | 15 | 2006 Italian Grand Prix 🇮🇹 | 2006-09-10 | 10 | R | 43 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2006 | 14 | 2006 Turkish Grand Prix 🇹🇷 | 2006-08-27 | 3 | 2 | 58 | +5.575 | Felipe Massa 🇧🇷 | Ferrari 🇮🇹 |
| 2006 | 13 | 2006 Hungarian Grand Prix 🇭🇺 | 2006-08-06 | 15 | R | 51 |   | Jenson Button 🇬🇧 | Honda 🇯🇵 |
| 2006 | 12 | 2006 German Grand Prix 🇩🇪 | 2006-07-30 | 7 | 5 | 67 | +23.7 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2006 | 11 | 2006 French Grand Prix 🇫🇷 | 2006-07-16 | 3 | 2 | 70 | +10.1 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2006 | 10 | 2006 United States Grand Prix 🇺🇸 | 2006-07-02 | 5 | 5 | 73 | +28.410 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2006 | 9 | 2006 Canadian Grand Prix 🇨🇦 | 2006-06-25 | 1 | 1 | 70 | 1:34:37.308 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2006 | 8 | 2006 British Grand Prix 🇬🇧 | 2006-06-11 | 1 | 1 | 60 | 1:25:51.927 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2006 | 7 | 2006 Monaco Grand Prix 🇲🇨 | 2006-05-28 | 1 | 1 | 78 | 1:43:43.116 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2006 | 6 | 2006 Spanish Grand Prix 🇪🇸 | 2006-05-14 | 1 | 1 | 66 | 1:26:21.759 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2006 | 5 | 2006 European Grand Prix 🇩🇪 | 2006-05-07 | 1 | 2 | 60 | +3.751 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2006 | 4 | 2006 San Marino Grand Prix 🇮🇹 | 2006-04-23 | 5 | 2 | 62 | +2.096 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2006 | 3 | 2006 Australian Grand Prix 🇦🇺 | 2006-04-02 | 3 | 1 | 57 | 1:34:27.870 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2006 | 2 | 2006 Malaysian Grand Prix 🇲🇾 | 2006-03-19 | 7 | 2 | 56 | +4.585 | Giancarlo Fisichella 🇮🇹 | Renault 🇫🇷 |
| 2006 | 1 | 2006 Bahrain Grand Prix 🇧🇭 | 2006-03-12 | 4 | 1 | 57 | 1:29:46.205 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 19 | 2005 Chinese Grand Prix 🇨🇳 | 2005-10-16 | 1 | 1 | 56 | 1:39:53.618 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 18 | 2005 Japanese Grand Prix 🇯🇵 | 2005-10-09 | 16 | 3 | 53 | +17.456 | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2005 | 17 | 2005 Brazilian Grand Prix 🇧🇷 | 2005-09-25 | 1 | 3 | 71 | +24.840 | Juan Pablo Montoya 🇨🇴 | McLaren 🇬🇧 |
| 2005 | 16 | 2005 Belgian Grand Prix 🇧🇪 | 2005-09-11 | 4 | 2 | 44 | +28.3 | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2005 | 15 | 2005 Italian Grand Prix 🇮🇹 | 2005-09-04 | 2 | 2 | 53 | +2.479 | Juan Pablo Montoya 🇨🇴 | McLaren 🇬🇧 |
| 2005 | 14 | 2005 Turkish Grand Prix 🇹🇷 | 2005-08-21 | 3 | 2 | 58 | +18.609 | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2005 | 13 | 2005 Hungarian Grand Prix 🇭🇺 | 2005-07-31 | 6 | 11 | 69 |   | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2005 | 12 | 2005 German Grand Prix 🇩🇪 | 2005-07-24 | 3 | 1 | 67 | 1:26:28.599 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 11 | 2005 British Grand Prix 🇬🇧 | 2005-07-10 | 1 | 2 | 60 | +2.7 | Juan Pablo Montoya 🇨🇴 | McLaren 🇬🇧 |
| 2005 | 10 | 2005 French Grand Prix 🇫🇷 | 2005-07-03 | 1 | 1 | 70 | 1:31:22.232 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 9 | 2005 United States Grand Prix 🇺🇸 | 2005-06-19 | 6 | W | 0 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2005 | 8 | 2005 Canadian Grand Prix 🇨🇦 | 2005-06-12 | 3 | R | 38 |   | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2005 | 7 | 2005 European Grand Prix 🇩🇪 | 2005-05-29 | 6 | 1 | 59 | 1:31:46.648 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 6 | 2005 Monaco Grand Prix 🇲🇨 | 2005-05-22 | 2 | 4 | 78 | +36.487 | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2005 | 5 | 2005 Spanish Grand Prix 🇪🇸 | 2005-05-08 | 3 | 2 | 66 | +27.652 | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2005 | 4 | 2005 San Marino Grand Prix 🇮🇹 | 2005-04-24 | 2 | 1 | 62 | 1:27:41.921 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 3 | 2005 Bahrain Grand Prix 🇧🇭 | 2005-04-03 | 1 | 1 | 57 | 1:29:18.531 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 2 | 2005 Malaysian Grand Prix 🇲🇾 | 2005-03-20 | 1 | 1 | 56 | 1:31:33.736 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2005 | 1 | 2005 Australian Grand Prix 🇦🇺 | 2005-03-06 | 13 | 3 | 57 | +6.712 | Giancarlo Fisichella 🇮🇹 | Renault 🇫🇷 |
| 2004 | 18 | 2004 Brazilian Grand Prix 🇧🇷 | 2004-10-24 | 8 | 4 | 71 | +48.508 | Juan Pablo Montoya 🇨🇴 | Williams 🇬🇧 |
| 2004 | 17 | 2004 Japanese Grand Prix 🇯🇵 | 2004-10-10 | 11 | 5 | 53 | +37.767 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 16 | 2004 Chinese Grand Prix 🇨🇳 | 2004-09-26 | 6 | 4 | 56 | +32.510 | Rubens Barrichello 🇧🇷 | Ferrari 🇮🇹 |
| 2004 | 15 | 2004 Italian Grand Prix 🇮🇹 | 2004-09-12 | 4 | R | 40 |   | Rubens Barrichello 🇧🇷 | Ferrari 🇮🇹 |
| 2004 | 14 | 2004 Belgian Grand Prix 🇧🇪 | 2004-08-29 | 3 | R | 11 |   | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2004 | 13 | 2004 Hungarian Grand Prix 🇭🇺 | 2004-08-15 | 5 | 3 | 70 | +44.599 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 12 | 2004 German Grand Prix 🇩🇪 | 2004-07-25 | 5 | 3 | 66 | +16.351 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 11 | 2004 British Grand Prix 🇬🇧 | 2004-07-11 | 16 | 10 | 60 | +24.835 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 10 | 2004 French Grand Prix 🇫🇷 | 2004-07-04 | 1 | 2 | 70 | +8.329 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 9 | 2004 United States Grand Prix 🇺🇸 | 2004-06-20 | 9 | R | 8 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 8 | 2004 Canadian Grand Prix 🇨🇦 | 2004-06-13 | 5 | R | 44 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 7 | 2004 European Grand Prix 🇩🇪 | 2004-05-30 | 6 | 5 | 60 | +1:00.987 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 6 | 2004 Monaco Grand Prix 🇲🇨 | 2004-05-23 | 3 | R | 41 |   | Jarno Trulli 🇮🇹 | Renault 🇫🇷 |
| 2004 | 5 | 2004 Spanish Grand Prix 🇪🇸 | 2004-05-09 | 8 | 4 | 66 | +32.952 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 4 | 2004 San Marino Grand Prix 🇮🇹 | 2004-04-25 | 6 | 4 | 62 | +23.654 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 3 | 2004 Bahrain Grand Prix 🇧🇭 | 2004-04-04 | 16 | 6 | 57 | +53.156 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 2 | 2004 Malaysian Grand Prix 🇲🇾 | 2004-03-21 | 19 | 7 | 56 | +1:07.877 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2004 | 1 | 2004 Australian Grand Prix 🇦🇺 | 2004-03-07 | 5 | 3 | 58 | +34.673 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2003 | 16 | 2003 Japanese Grand Prix 🇯🇵 | 2003-10-12 | 5 | R | 17 |   | Rubens Barrichello 🇧🇷 | Ferrari 🇮🇹 |
| 2003 | 15 | 2003 United States Grand Prix 🇺🇸 | 2003-09-28 | 6 | R | 44 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2003 | 14 | 2003 Italian Grand Prix 🇮🇹 | 2003-09-14 | 20 | 8 | 52 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2003 | 13 | 2003 Hungarian Grand Prix 🇭🇺 | 2003-08-24 | 1 | 1 | 70 | 1:39:01.460 | Fernando Alonso 🇪🇸 | Renault 🇫🇷 |
| 2003 | 12 | 2003 German Grand Prix 🇩🇪 | 2003-08-03 | 8 | 4 | 67 | +1:09.344 | Juan Pablo Montoya 🇨🇴 | Williams 🇬🇧 |
| 2003 | 11 | 2003 British Grand Prix 🇬🇧 | 2003-07-20 | 8 | R | 52 |   | Rubens Barrichello 🇧🇷 | Ferrari 🇮🇹 |
| 2003 | 10 | 2003 French Grand Prix 🇫🇷 | 2003-07-06 | 7 | R | 43 |   | Ralf Schumacher 🇩🇪 | Williams 🇬🇧 |
| 2003 | 9 | 2003 European Grand Prix 🇩🇪 | 2003-06-29 | 8 | 4 | 60 | +1:05.731 | Ralf Schumacher 🇩🇪 | Williams 🇬🇧 |
| 2003 | 8 | 2003 Canadian Grand Prix 🇨🇦 | 2003-06-15 | 4 | 4 | 70 | +4.481 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2003 | 7 | 2003 Monaco Grand Prix 🇲🇨 | 2003-06-01 | 8 | 5 | 78 | +36.251 | Juan Pablo Montoya 🇨🇴 | Williams 🇬🇧 |
| 2003 | 6 | 2003 Austrian Grand Prix 🇦🇹 | 2003-05-18 | 19 | R | 44 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2003 | 5 | 2003 Spanish Grand Prix 🇪🇸 | 2003-05-04 | 3 | 2 | 65 | +5.7 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2003 | 4 | 2003 San Marino Grand Prix 🇮🇹 | 2003-04-20 | 8 | 6 | 62 | +43.689 | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2003 | 3 | 2003 Brazilian Grand Prix 🇧🇷 | 2003-04-06 | 10 | 3 | 54 | +6.348 | Giancarlo Fisichella 🇮🇹 | Jordan 🇮🇪 |
| 2003 | 2 | 2003 Malaysian Grand Prix 🇲🇾 | 2003-03-23 | 1 | 3 | 56 | +1:04.007 | Kimi Räikkönen 🇫🇮 | McLaren 🇬🇧 |
| 2003 | 1 | 2003 Australian Grand Prix 🇦🇺 | 2003-03-09 | 10 | 7 | 58 | +45.074 | David Coulthard 🇬🇧 | McLaren 🇬🇧 |
| 2001 | 17 | 2001 Japanese Grand Prix 🇯🇵 | 2001-10-14 | 18 | 11 | 52 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 16 | 2001 United States Grand Prix 🇺🇸 | 2001-09-30 | 17 | R | 36 |   | Mika Häkkinen 🇫🇮 | McLaren 🇬🇧 |
| 2001 | 15 | 2001 Italian Grand Prix 🇮🇹 | 2001-09-16 | 21 | 13 | 51 |   | Juan Pablo Montoya 🇨🇴 | Williams 🇬🇧 |
| 2001 | 14 | 2001 Belgian Grand Prix 🇧🇪 | 2001-09-02 | 20 | R | 0 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 13 | 2001 Hungarian Grand Prix 🇭🇺 | 2001-08-19 | 18 | R | 37 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 12 | 2001 German Grand Prix 🇩🇪 | 2001-07-29 | 21 | 10 | 44 |   | Ralf Schumacher 🇩🇪 | Williams 🇬🇧 |
| 2001 | 11 | 2001 British Grand Prix 🇬🇧 | 2001-07-15 | 21 | 16 | 57 |   | Mika Häkkinen 🇫🇮 | McLaren 🇬🇧 |
| 2001 | 10 | 2001 French Grand Prix 🇫🇷 | 2001-07-01 | 21 | 17 | 65 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 9 | 2001 European Grand Prix 🇩🇪 | 2001-06-24 | 21 | 14 | 65 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 8 | 2001 Canadian Grand Prix 🇨🇦 | 2001-06-10 | 22 | R | 7 |   | Ralf Schumacher 🇩🇪 | Williams 🇬🇧 |
| 2001 | 7 | 2001 Monaco Grand Prix 🇲🇨 | 2001-05-27 | 18 | R | 54 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 6 | 2001 Austrian Grand Prix 🇦🇹 | 2001-05-13 | 18 | R | 38 |   | David Coulthard 🇬🇧 | McLaren 🇬🇧 |
| 2001 | 5 | 2001 Spanish Grand Prix 🇪🇸 | 2001-04-29 | 18 | 13 | 63 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 4 | 2001 San Marino Grand Prix 🇮🇹 | 2001-04-15 | 18 | R | 5 |   | Ralf Schumacher 🇩🇪 | Williams 🇬🇧 |
| 2001 | 3 | 2001 Brazilian Grand Prix 🇧🇷 | 2001-04-01 | 19 | R | 25 |   | David Coulthard 🇬🇧 | McLaren 🇬🇧 |
| 2001 | 2 | 2001 Malaysian Grand Prix 🇲🇾 | 2001-03-18 | 21 | 13 | 52 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 2001 | 1 | 2001 Australian Grand Prix 🇦🇺 | 2001-03-04 | 19 | 12 | 56 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 274 |  |  | 274 | 228 | 274 | 137 |  |  |
| **Total Sum** | 2686.000 |  |  | 2156.000 | 1217.000 | 14963.000 | 3269.080 |  |  |
| **Mean μ (Average)** | 9.803 |  |  | 7.869 | 5.338 | 54.609 | 23.862 |  |  |
| **Maximum** | 21.000 |  |  | 24.000 | 18.000 | 78.000 | 59.946 |  |  |
| **75th Percentile** | 14.000 |  |  | 10.000 | 7.000 | 66.000 | 35.992 |  |  |
| **Median** | 10.000 |  |  | 6.000 | 4.000 | 57.000 | 20.594 |  |  |
| **25th Percentile** | 5.000 |  |  | 4.000 | 2.000 | 52.000 | 9.806 |  |  |
| **Minimum** | 1.000 |  |  | 1.000 | 1.000 |  | 0.852 |  |  |
| **Variance** | 28.625 |  |  | 31.662 | 16.496 | 272.377 | 276.659 |  |  |
| **Standard Deviation σ** | 5.350 |  |  | 5.627 | 4.061 | 16.504 | 16.633 |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
