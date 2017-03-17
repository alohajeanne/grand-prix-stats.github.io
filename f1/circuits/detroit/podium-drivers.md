---
title: Rank of Formula 1® Drivers by Number of Podiums at Detroit Street Circuit
layout: page
rowCount: 13
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935"
            ],
            "borderColor": [
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
                3.0,
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
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Alain Prost",
        "Ayrton Senna",
        "John Watson",
        "Keke Rosberg",
        "Michele Alboreto",
        "Nelson Piquet",
        "Didier Pironi",
        "Eddie Cheever",
        "Elio de Angelis",
        "Jacques Laffite",
        "Stefan Johansson",
        "Teo Fabi",
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

<!-- div id="chart-navigation">
<button onclick="window.location = chart.toBase64Image();">Save as Image</button>
<button onclick="window.location = chart.toBase64Image();">Hello</button>
<button onclick="window.location = chart.toBase64Image();">Hello</button>
<select>
<option>one</option>
<option>two</option>
<option>three</option>
</select>
</div -->




### Data Table

| # | Driver | Number Of Podiums |
|--|--|--|
| 1. | Alain Prost 🇫🇷 | 3 |
| 2. | Ayrton Senna 🇧🇷 | 3 |
| 3. | John Watson 🇬🇧 | 2 |
| 4. | Keke Rosberg 🇫🇮 | 2 |
| 5. | Michele Alboreto 🇮🇹 | 2 |
| 6. | Nelson Piquet 🇧🇷 | 2 |
| 7. | Didier Pironi 🇫🇷 | 1 |
| 8. | Eddie Cheever 🇺🇸 | 1 |
| 9. | Elio de Angelis 🇮🇹 | 1 |
| 10. | Jacques Laffite 🇫🇷 | 1 |
| 11. | Stefan Johansson 🇸🇪 | 1 |
| 12. | Teo Fabi 🇮🇹 | 1 |
| 13. | Thierry Boutsen 🇧🇪 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
