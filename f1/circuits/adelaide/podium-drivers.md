---
title: Rank of Formula 1® Drivers by Number of Podiums at Adelaide Street Circuit
layout: page
rowCount: 18
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
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                4.0,
                4.0,
                3.0,
                3.0,
                3.0,
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
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Alain Prost",
        "Gerhard Berger",
        "Ayrton Senna",
        "Nelson Piquet",
        "Nigel Mansell",
        "Damon Hill",
        "Martin Brundle",
        "Thierry Boutsen",
        "Alessandro Nannini",
        "Gianni Morbidelli",
        "Jacques Laffite",
        "Keke Rosberg",
        "Michael Schumacher",
        "Michele Alboreto",
        "Olivier Panis",
        "Philippe Streiff",
        "Riccardo Patrese",
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
| 1. | Alain Prost 🇫🇷 | 4 |
| 2. | Gerhard Berger 🇦🇹 | 4 |
| 3. | Ayrton Senna 🇧🇷 | 3 |
| 4. | Nelson Piquet 🇧🇷 | 3 |
| 5. | Nigel Mansell 🇬🇧 | 3 |
| 6. | Damon Hill 🇬🇧 | 2 |
| 7. | Martin Brundle 🇬🇧 | 2 |
| 8. | Thierry Boutsen 🇧🇪 | 2 |
| 9. | Alessandro Nannini 🇮🇹 | 1 |
| 10. | Gianni Morbidelli 🇮🇹 | 1 |
| 11. | Jacques Laffite 🇫🇷 | 1 |
| 12. | Keke Rosberg 🇫🇮 | 1 |
| 13. | Michael Schumacher 🇩🇪 | 1 |
| 14. | Michele Alboreto 🇮🇹 | 1 |
| 15. | Olivier Panis 🇫🇷 | 1 |
| 16. | Philippe Streiff 🇫🇷 | 1 |
| 17. | Riccardo Patrese 🇮🇹 | 1 |
| 18. | Stefan Johansson 🇸🇪 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
