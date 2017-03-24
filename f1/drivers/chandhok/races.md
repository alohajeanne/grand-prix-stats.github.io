---
title: List of Formula 1® Races by Karun Chandhok
layout: page
collectionName: drivers
collectionId: chandhok
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
| 2011 | 10 | 2011 German Grand Prix 🇩🇪 | 2011-07-24 | 20 | 20 | 56 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 10 | 2010 British Grand Prix 🇬🇧 | 2010-07-11 | 23 | 19 | 50 |   | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2010 | 9 | 2010 European Grand Prix 🇪🇸 | 2010-06-27 | 23 | 18 | 55 |   | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 8 | 2010 Canadian Grand Prix 🇨🇦 | 2010-06-13 | 24 | 18 | 66 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 7 | 2010 Turkish Grand Prix 🇹🇷 | 2010-05-30 | 24 | 20 | 52 |   | Lewis Hamilton 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 6 | 2010 Monaco Grand Prix 🇲🇨 | 2010-05-16 | 23 | 14 | 70 |   | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2010 | 5 | 2010 Spanish Grand Prix 🇪🇸 | 2010-05-09 | 24 | R | 27 |   | Mark Webber 🇦🇺 | Red Bull 🇦🇹 |
| 2010 | 4 | 2010 Chinese Grand Prix 🇨🇳 | 2010-04-18 | 24 | 17 | 52 |   | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 3 | 2010 Malaysian Grand Prix 🇲🇾 | 2010-04-04 | 22 | 15 | 53 |   | Sebastian Vettel 🇩🇪 | Red Bull 🇦🇹 |
| 2010 | 2 | 2010 Australian Grand Prix 🇦🇺 | 2010-03-28 | 22 | 14 | 53 |   | Jenson Button 🇬🇧 | McLaren 🇬🇧 |
| 2010 | 1 | 2010 Bahrain Grand Prix 🇧🇭 | 2010-03-14 | 24 | R | 1 |   | Fernando Alonso 🇪🇸 | Ferrari 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 11 |  |  | 11 | 9 | 11 |  |  |  |
| **Total Sum** | 65.000 |  |  | 253.000 | 155.000 | 535.000 |  |  |  |
| **Mean μ (Average)** | 5.909 |  |  | 23.000 | 17.222 | 48.636 |  |  |  |
| **Maximum** | 10.000 |  |  | 24.000 | 20.000 | 70.000 |  |  |  |
| **75th Percentile** | 9.000 |  |  | 24.000 | 19.000 | 56.000 |  |  |  |
| **Median** | 6.000 |  |  | 23.000 | 18.000 | 53.000 |  |  |  |
| **25th Percentile** | 3.000 |  |  | 22.000 | 15.000 | 50.000 |  |  |  |
| **Minimum** | 1.000 |  |  | 20.000 | 14.000 | 1.000 |  |  |  |
| **Variance** | 9.174 |  |  | 1.455 | 5.062 | 332.050 |  |  |  |
| **Standard Deviation σ** | 3.029 |  |  | 1.206 | 2.250 | 18.222 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
