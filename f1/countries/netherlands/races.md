---
title: List of All Formula 1® Races in Netherlands by Year
layout: page
collectionName: countries
collectionId: netherlands
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

| Season | Round | Name | Circuit | Date | Laps Completed | Race Duration | Winning Driver | Winning Constructor |
|--|--|--|--|--|--|--|--|--|
| 1985 | 11 | 1985 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1985-08-25 | 70 | 1:32:29.263 | Niki Lauda 🇦🇹 | McLaren 🇬🇧 |
| 1984 | 13 | 1984 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1984-08-26 | 71 | 1:37:21.468 | Alain Prost 🇫🇷 | McLaren 🇬🇧 |
| 1983 | 12 | 1983 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1983-08-28 | 72 | 1:38:41.950 | René Arnoux 🇫🇷 | Ferrari 🇮🇹 |
| 1982 | 9 | 1982 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1982-07-03 | 72 | 1:38:03.254 | Didier Pironi 🇫🇷 | Ferrari 🇮🇹 |
| 1981 | 12 | 1981 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1981-08-30 | 72 | 1:40:22.43 | Alain Prost 🇫🇷 | Renault 🇫🇷 |
| 1980 | 11 | 1980 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1980-08-31 | 72 | 1:38:13.83 | Nelson Piquet 🇧🇷 | Brabham 🇬🇧 |
| 1979 | 12 | 1979 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1979-08-26 | 75 | 1:41:19.775 | Alan Jones 🇦🇺 | Williams 🇬🇧 |
| 1978 | 13 | 1978 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1978-08-27 | 75 | 1:41:04.23 | Mario Andretti 🇺🇸 | Team Lotus 🇬🇧 |
| 1977 | 13 | 1977 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1977-08-28 | 75 | 1:41:45.93 | Niki Lauda 🇦🇹 | Ferrari 🇮🇹 |
| 1976 | 12 | 1976 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1976-08-29 | 75 | 1:44:52.09 | James Hunt 🇬🇧 | McLaren 🇬🇧 |
| 1975 | 8 | 1975 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1975-06-22 | 75 | 1:46:57.40 | James Hunt 🇬🇧 | Hesketh 🇬🇧 |
| 1974 | 8 | 1974 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1974-06-23 | 75 | 1:43:00.35 | Niki Lauda 🇦🇹 | Ferrari 🇮🇹 |
| 1973 | 10 | 1973 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1973-07-29 | 72 | 1:39:12.45 | Jackie Stewart 🇬🇧 | Tyrrell 🇬🇧 |
| 1971 | 4 | 1971 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1971-06-20 | 70 | 1:56:20.0 | Jacky Ickx 🇧🇪 | Ferrari 🇮🇹 |
| 1970 | 5 | 1970 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1970-06-21 | 80 | 1:50:43.4 | Jochen Rindt 🇦🇹 | Team Lotus 🇬🇧 |
| 1969 | 4 | 1969 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1969-06-21 | 90 | 2:06:42.08 | Jackie Stewart 🇬🇧 | Matra-Ford 🇫🇷 |
| 1968 | 5 | 1968 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1968-06-23 | 90 | 2:46:11.2 | Jackie Stewart 🇬🇧 | Matra-Ford 🇫🇷 |
| 1967 | 3 | 1967 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1967-06-04 | 90 | 2:14:45.1 | Jim Clark 🇬🇧 | Lotus-Ford 🇬🇧 |
| 1966 | 5 | 1966 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1966-07-24 | 90 | 2:20:32.5 | Jack Brabham 🇦🇺 | Brabham-Repco 🇬🇧 |
| 1965 | 6 | 1965 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1965-07-18 | 80 | 2:03:59.1 | Jim Clark 🇬🇧 | Lotus-Climax 🇬🇧 |
| 1964 | 2 | 1964 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1964-05-24 | 80 | 2:07:35.4 | Jim Clark 🇬🇧 | Lotus-Climax 🇬🇧 |
| 1963 | 3 | 1963 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1963-06-23 | 80 | 2:08:13.7 | Jim Clark 🇬🇧 | Lotus-Climax 🇬🇧 |
| 1962 | 1 | 1962 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1962-05-20 | 80 | 2:11:02.1 | Graham Hill 🇬🇧 | BRM 🇬🇧 |
| 1961 | 2 | 1961 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1961-05-22 | 75 | 2:01:52.1 | Wolfgang von Trips 🇩🇪 | Ferrari 🇮🇹 |
| 1960 | 4 | 1960 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1960-06-06 | 75 | 2:01:47.2 | Jack Brabham 🇦🇺 | Cooper-Climax 🇬🇧 |
| 1959 | 3 | 1959 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1959-05-31 | 75 | 2:05:26.8 | Jo Bonnier 🇸🇪 | BRM 🇬🇧 |
| 1958 | 3 | 1958 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1958-05-26 | 75 | 2:04:49.2 | Stirling Moss 🇬🇧 | Vanwall 🇬🇧 |
| 1955 | 5 | 1955 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1955-06-19 | 100 | 2:54:23.8 | Juan Fangio 🇦🇷 | Mercedes 🇩🇪 |
| 1953 | 3 | 1953 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1953-06-07 | 90 | 2:53:35.8 | Alberto Ascari 🇮🇹 | Ferrari 🇮🇹 |
| 1952 | 7 | 1952 Dutch Grand Prix 🇳🇱 | [Circuit Park Zandvoort](/f1/circuits/zandvoort) | 1952-08-17 | 90 | 2:53:28.5 | Alberto Ascari 🇮🇹 | Ferrari 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Circuit** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 30 |  |  |  | 30 |  |  |  |
| **Total Sum** | 209.000 |  |  |  | 2361.000 |  |  |  |
| **Mean μ (Average)** | 6.967 |  |  |  | 78.700 |  |  |  |
| **Maximum** | 13.000 |  |  |  | 100.000 |  |  |  |
| **75th Percentile** | 11.000 |  |  |  | 80.000 |  |  |  |
| **Median** | 6.000 |  |  |  | 75.000 |  |  |  |
| **25th Percentile** | 3.000 |  |  |  | 72.000 |  |  |  |
| **Minimum** | 1.000 |  |  |  | 70.000 |  |  |  |
| **Variance** | 15.499 |  |  |  | 60.010 |  |  |  |
| **Standard Deviation σ** | 3.937 |  |  |  | 7.747 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
