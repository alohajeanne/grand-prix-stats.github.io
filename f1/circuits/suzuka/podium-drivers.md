---
title: Rank of Formula 1® Drivers by Number of Podiums at Suzuka Circuit
layout: page
collectionName: circuits
collectionId: suzuka
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

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D"
            ],
            "borderColor": [
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                9.0,
                7.0,
                6.0,
                4.0,
                4.0,
                4.0,
                4.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Sebastian Vettel",
        "Mika Häkkinen",
        "Ayrton Senna",
        "David Coulthard",
        "Fernando Alonso",
        "Lewis Hamilton",
        "Eddie Irvine",
        "Gerhard Berger",
        "Kimi Räikkönen",
        "Nico Rosberg",
        "Riccardo Patrese",
        "Alain Prost",
        "Damon Hill",
        "Felipe Massa",
        "Giancarlo Fisichella",
        "Jenson Button",
        "Mark Webber",
        "Rubens Barrichello",
        "Thierry Boutsen",
        "Aguri Suzuki",
        "Alessandro Nannini",
        "Heinz-Harald Frentzen",
        "Jarno Trulli",
        "Jean Alesi",
        "Johnny Herbert",
        "Juan Pablo Montoya",
        "Kamui Kobayashi",
        "Martin Brundle",
        "Max Verstappen",
        "Nelson Piquet",
        "Ralf Schumacher",
        "Roberto Moreno",
        "Romain Grosjean",
        "Stefan Johansson"
    ]
};
var options = {
  legend: {
    display: false
  },
  scales: {
    xAxes: [{
      ticks: {
        beginAtZero: true,
        maxRotation: 180,
        display: window.innerWidth > 800
      }
    }],
    yAxes: [{
      ticks: {
        beginAtZero: true
      }
    }]
  },
  onResize: function(chart, size) {
    chart.options.scales.xAxes[0].ticks.display = size.width > 800;
  }
};
var chart = new Chart("chart", {
    data: data,
    type: 'bar',
    options: options
});
</script>



### Data Table

| # | Driver | Number Of Podiums |
|--|--|--|
| 1. | Michael Schumacher 🇩🇪 | 9 |
| 2. | Sebastian Vettel 🇩🇪 | 7 |
| 3. | Mika Häkkinen 🇫🇮 | 6 |
| 4. | Ayrton Senna 🇧🇷 | 4 |
| 5. | David Coulthard 🇬🇧 | 4 |
| 6. | Fernando Alonso 🇪🇸 | 4 |
| 7. | Lewis Hamilton 🇬🇧 | 4 |
| 8. | Eddie Irvine 🇬🇧 | 3 |
| 9. | Gerhard Berger 🇦🇹 | 3 |
| 10. | Kimi Räikkönen 🇫🇮 | 3 |
| 11. | Nico Rosberg 🇩🇪 | 3 |
| 12. | Riccardo Patrese 🇮🇹 | 3 |
| 13. | Alain Prost 🇫🇷 | 2 |
| 14. | Damon Hill 🇬🇧 | 2 |
| 15. | Felipe Massa 🇧🇷 | 2 |
| 16. | Giancarlo Fisichella 🇮🇹 | 2 |
| 17. | Jenson Button 🇬🇧 | 2 |
| 18. | Mark Webber 🇦🇺 | 2 |
| 19. | Rubens Barrichello 🇧🇷 | 2 |
| 20. | Thierry Boutsen 🇧🇪 | 2 |
| 21. | Aguri Suzuki 🇯🇵 | 1 |
| 22. | Alessandro Nannini 🇮🇹 | 1 |
| 23. | Heinz-Harald Frentzen 🇩🇪 | 1 |
| 24. | Jarno Trulli 🇮🇹 | 1 |
| 25. | Jean Alesi 🇫🇷 | 1 |
| 26. | Johnny Herbert 🇬🇧 | 1 |
| 27. | Juan Pablo Montoya 🇨🇴 | 1 |
| 28. | Kamui Kobayashi 🇯🇵 | 1 |
| 29. | Martin Brundle 🇬🇧 | 1 |
| 30. | Max Verstappen 🇳🇱 | 1 |
| 31. | Nelson Piquet 🇧🇷 | 1 |
| 32. | Ralf Schumacher 🇩🇪 | 1 |
| 33. | Roberto Moreno 🇧🇷 | 1 |
| 34. | Romain Grosjean 🇫🇷 | 1 |
| 35. | Stefan Johansson 🇸🇪 | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 35 |
| **Total Sum** | 84.000 |
| **Mean μ (Average)** | 2.400 |
| **Maximum** | 9.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 3.440 |
| **Standard Deviation σ** | 1.855 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
