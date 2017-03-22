---
title: Rank of Formula 1® Drivers by Number of Podiums at Autódromo do Estoril
layout: page
collectionName: circuits
collectionId: estoril
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
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                7.0,
                5.0,
                4.0,
                3.0,
                3.0,
                3.0,
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
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Alain Prost",
        "Ayrton Senna",
        "Damon Hill",
        "Gerhard Berger",
        "Michael Schumacher",
        "Nigel Mansell",
        "David Coulthard",
        "Nelson Piquet",
        "Ivan Capelli",
        "Jacques Villeneuve",
        "Jean Alesi",
        "Michele Alboreto",
        "Mika Häkkinen",
        "Niki Lauda",
        "Patrick Tambay",
        "Riccardo Patrese",
        "Stefan Johansson",
        "Thierry Boutsen"
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
| 1. | Alain Prost 🇫🇷 | 7 |
| 2. | Ayrton Senna 🇧🇷 | 5 |
| 3. | Damon Hill 🇬🇧 | 4 |
| 4. | Gerhard Berger 🇦🇹 | 3 |
| 5. | Michael Schumacher 🇩🇪 | 3 |
| 6. | Nigel Mansell 🇬🇧 | 3 |
| 7. | David Coulthard 🇬🇧 | 2 |
| 8. | Nelson Piquet 🇧🇷 | 2 |
| 9. | Ivan Capelli 🇮🇹 | 1 |
| 10. | Jacques Villeneuve 🇨🇦 | 1 |
| 11. | Jean Alesi 🇫🇷 | 1 |
| 12. | Michele Alboreto 🇮🇹 | 1 |
| 13. | Mika Häkkinen 🇫🇮 | 1 |
| 14. | Niki Lauda 🇦🇹 | 1 |
| 15. | Patrick Tambay 🇫🇷 | 1 |
| 16. | Riccardo Patrese 🇮🇹 | 1 |
| 17. | Stefan Johansson 🇸🇪 | 1 |
| 18. | Thierry Boutsen 🇧🇪 | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 18 |
| **Total Sum** | 39.000 |
| **Mean μ (Average)** | 2.167 |
| **Maximum** | 7.000 |
| **75th Percentile** | 3.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 2.806 |
| **Standard Deviation σ** | 1.675 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
