---
title: List of Formula 1® Races by Andrea Montermini
layout: page
collectionName: drivers
collectionId: montermini
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
| 1996 | 10 | 1996 British Grand Prix 🇬🇧 | 1996-07-14 | 21 | F | 0 |   | Jacques Villeneuve 🇨🇦 | Williams 🇬🇧 |
| 1996 | 9 | 1996 French Grand Prix 🇫🇷 | 1996-06-30 | 21 | R | 2 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1996 | 8 | 1996 Canadian Grand Prix 🇨🇦 | 1996-06-16 | 22 | R | 22 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1996 | 7 | 1996 Spanish Grand Prix 🇪🇸 | 1996-06-02 | 22 | F | 0 |   | Michael Schumacher 🇩🇪 | Ferrari 🇮🇹 |
| 1996 | 6 | 1996 Monaco Grand Prix 🇲🇨 | 1996-05-19 | 22 | W | 0 |   | Olivier Panis 🇫🇷 | Ligier 🇫🇷 |
| 1996 | 5 | 1996 San Marino Grand Prix 🇮🇹 | 1996-05-05 | 22 | F | 0 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1996 | 4 | 1996 European Grand Prix 🇩🇪 | 1996-04-28 | 21 | F | 0 |   | Jacques Villeneuve 🇨🇦 | Williams 🇬🇧 |
| 1996 | 3 | 1996 Argentine Grand Prix 🇦🇷 | 1996-04-07 | 22 | 10 | 69 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1996 | 2 | 1996 Brazilian Grand Prix 🇧🇷 | 1996-03-31 | 20 | R | 26 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1996 | 1 | 1996 Australian Grand Prix 🇦🇺 | 1996-03-10 | 22 | F | 0 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1995 | 17 | 1995 Australian Grand Prix 🇦🇺 | 1995-11-12 | 22 | R | 2 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1995 | 16 | 1995 Japanese Grand Prix 🇯🇵 | 1995-10-29 | 19 | R | 23 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 15 | 1995 Pacific Grand Prix 🇯🇵 | 1995-10-22 | 23 | R | 14 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 14 | 1995 European Grand Prix 🇩🇪 | 1995-10-01 | 20 | R | 45 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 13 | 1995 Portuguese Grand Prix 🇵🇹 | 1995-09-24 | 21 | R | 53 |   | David Coulthard 🇬🇧 | Williams 🇬🇧 |
| 1995 | 12 | 1995 Italian Grand Prix 🇮🇹 | 1995-09-10 | 21 | R | 0 |   | Johnny Herbert 🇬🇧 | Benetton 🇮🇹 |
| 1995 | 11 | 1995 Belgian Grand Prix 🇧🇪 | 1995-08-27 | 21 | R | 18 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 10 | 1995 Hungarian Grand Prix 🇭🇺 | 1995-08-13 | 22 | 12 | 73 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1995 | 9 | 1995 German Grand Prix 🇩🇪 | 1995-07-30 | 23 | 8 | 42 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 8 | 1995 British Grand Prix 🇬🇧 | 1995-07-16 | 24 | R | 21 |   | Johnny Herbert 🇬🇧 | Benetton 🇮🇹 |
| 1995 | 7 | 1995 French Grand Prix 🇫🇷 | 1995-07-02 | 21 | N | 62 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 6 | 1995 Canadian Grand Prix 🇨🇦 | 1995-06-11 | 21 | R | 5 |   | Jean Alesi 🇫🇷 | Ferrari 🇮🇹 |
| 1995 | 5 | 1995 Monaco Grand Prix 🇲🇨 | 1995-05-28 | 25 | D | 23 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 4 | 1995 Spanish Grand Prix 🇪🇸 | 1995-05-14 | 23 | W | 0 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1995 | 3 | 1995 San Marino Grand Prix 🇮🇹 | 1995-04-30 | 24 | R | 15 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1995 | 2 | 1995 Argentine Grand Prix 🇦🇷 | 1995-04-09 | 22 | R | 1 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |
| 1995 | 1 | 1995 Brazilian Grand Prix 🇧🇷 | 1995-03-26 | 22 | 9 | 65 |   | Michael Schumacher 🇩🇪 | Benetton 🇮🇹 |
| 1994 | 5 | 1994 Spanish Grand Prix 🇪🇸 | 1994-05-29 | 0 | W | 0 |   | Damon Hill 🇬🇧 | Williams 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 28 |  |  | 28 | 4 | 28 |  |  |  |
| **Total Sum** | 213.000 |  |  | 589.000 | 39.000 | 581.000 |  |  |  |
| **Mean μ (Average)** | 7.607 |  |  | 21.036 | 9.750 | 20.750 |  |  |  |
| **Maximum** | 17.000 |  |  | 25.000 | 12.000 | 73.000 |  |  |  |
| **75th Percentile** | 11.000 |  |  | 22.000 | 12.000 | 42.000 |  |  |  |
| **Median** | 7.000 |  |  | 22.000 | 10.000 | 15.000 |  |  |  |
| **25th Percentile** | 4.000 |  |  | 21.000 | 9.000 |  |  |  |  |
| **Minimum** | 1.000 |  |  |  | 8.000 |  |  |  |  |
| **Variance** | 20.524 |  |  | 17.963 | 2.188 | 576.402 |  |  |  |
| **Standard Deviation σ** | 4.530 |  |  | 4.238 | 1.479 | 24.008 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
