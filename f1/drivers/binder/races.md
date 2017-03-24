---
title: List of Formula 1® Races by Hans Binder
layout: page
collectionName: drivers
collectionId: binder
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
| 1978 | 12 | 1978 Austrian Grand Prix 🇦🇹 | 1978-08-13 | 0 | F | 0 |   | Ronnie Peterson 🇸🇪 | Team Lotus 🇬🇧 |
| 1977 | 17 | 1977 Japanese Grand Prix 🇯🇵 | 1977-10-23 | 21 | R | 1 |   | James Hunt 🇬🇧 | McLaren 🇬🇧 |
| 1977 | 16 | 1977 Canadian Grand Prix 🇨🇦 | 1977-10-09 | 24 | R | 31 |   | Jody Scheckter 🇿🇦 | Wolf 🇨🇦 |
| 1977 | 15 | 1977 United States Grand Prix 🇺🇸 | 1977-10-02 | 25 | 11 | 57 |   | James Hunt 🇬🇧 | McLaren 🇬🇧 |
| 1977 | 14 | 1977 Italian Grand Prix 🇮🇹 | 1977-09-11 | 0 | F | 0 |   | Mario Andretti 🇺🇸 | Team Lotus 🇬🇧 |
| 1977 | 13 | 1977 Dutch Grand Prix 🇳🇱 | 1977-08-28 | 18 | 8 | 73 |   | Niki Lauda 🇦🇹 | Ferrari 🇮🇹 |
| 1977 | 12 | 1977 Austrian Grand Prix 🇦🇹 | 1977-08-14 | 19 | 12 | 53 |   | Alan Jones 🇦🇺 | Shadow 🇬🇧 |
| 1977 | 6 | 1977 Monaco Grand Prix 🇲🇨 | 1977-05-22 | 19 | R | 41 |   | Jody Scheckter 🇿🇦 | Wolf 🇨🇦 |
| 1977 | 5 | 1977 Spanish Grand Prix 🇪🇸 | 1977-05-08 | 20 | 9 | 73 |   | Mario Andretti 🇺🇸 | Team Lotus 🇬🇧 |
| 1977 | 4 | 1977 United States Grand Prix West 🇺🇸 | 1977-04-03 | 19 | 11 | 77 |   | Mario Andretti 🇺🇸 | Team Lotus 🇬🇧 |
| 1977 | 3 | 1977 South African Grand Prix 🇿🇦 | 1977-03-05 | 19 | 11 | 77 |   | Niki Lauda 🇦🇹 | Ferrari 🇮🇹 |
| 1977 | 2 | 1977 Brazilian Grand Prix 🇧🇷 | 1977-01-23 | 20 | R | 32 |   | Carlos Reutemann 🇦🇷 | Ferrari 🇮🇹 |
| 1977 | 1 | 1977 Argentine Grand Prix 🇦🇷 | 1977-01-09 | 18 | R | 18 |   | Jody Scheckter 🇿🇦 | Wolf 🇨🇦 |
| 1976 | 16 | 1976 Japanese Grand Prix 🇯🇵 | 1976-10-24 | 25 | R | 49 |   | Mario Andretti 🇺🇸 | Team Lotus 🇬🇧 |
| 1976 | 11 | 1976 Austrian Grand Prix 🇦🇹 | 1976-08-15 | 19 | R | 47 |   | John Watson 🇬🇧 | Penske 🇺🇸 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Laps Completed** | **Time** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 15 |  |  | 15 | 6 | 15 |  |  |  |
| **Total Sum** | 147.000 |  |  | 266.000 | 62.000 | 629.000 |  |  |  |
| **Mean μ (Average)** | 9.800 |  |  | 17.733 | 10.333 | 41.933 |  |  |  |
| **Maximum** | 17.000 |  |  | 25.000 | 12.000 | 77.000 |  |  |  |
| **75th Percentile** | 15.000 |  |  | 21.000 | 11.000 | 73.000 |  |  |  |
| **Median** | 12.000 |  |  | 19.000 | 11.000 | 47.000 |  |  |  |
| **25th Percentile** | 4.000 |  |  | 18.000 | 9.000 | 18.000 |  |  |  |
| **Minimum** | 1.000 |  |  |  | 8.000 |  |  |  |  |
| **Variance** | 30.027 |  |  | 53.529 | 1.889 | 719.929 |  |  |  |
| **Standard Deviation σ** | 5.480 |  |  | 7.316 | 1.374 | 26.831 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
