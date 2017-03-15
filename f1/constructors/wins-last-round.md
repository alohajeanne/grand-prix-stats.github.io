---
title: Rank of Formula 1® Constructor Teams by Number of Wins in Last Round
layout: page
rowCount: 21
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "EB212E",
                "AAAAAA",
                "FFF8F6",
                "3da48e",
                "381ea0",
                "09630C",
                "274B72",
                "B21827",
                "243F73",
                "025839",
                "025839",
                "C0BEC3",
                "336667",
                "73C2FB",
                "243F73",
                "144D44",
                "273027",
                "1A2446",
                "FFFFFF",
                "AAAAAA",
                "F6CF00"
            ],
            "borderColor": [
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444"
            ],
            "borderWidth": 1,
            "data": [
                14.0,
                11.0,
                8.0,
                4.0,
                4.0,
                3.0,
                3.0,
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
                1.0
            ],
            "label": "Wins Last Round"
        }
    ],
    "labels": [
        "Ferrari",
        "McLaren",
        "Williams",
        "Mercedes",
        "Red Bull",
        "Team Lotus",
        "Tyrrell",
        "Alfa Romeo",
        "Brabham",
        "Lotus-Climax",
        "Lotus-Ford",
        "Maserati",
        "Vanwall",
        "Benetton",
        "Brabham-Climax",
        "BRM",
        "Cooper-Climax",
        "Cooper-Maserati",
        "Honda",
        "McLaren-Ford",
        "Renault"
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

| # | Constructor | Wins Last Round |
|--|--|--|
| 1. | Ferrari 🇮🇹 | 14 |
| 2. | McLaren 🇬🇧 | 11 |
| 3. | Williams 🇬🇧 | 8 |
| 4. | Mercedes 🇩🇪 | 4 |
| 5. | Red Bull 🇦🇹 | 4 |
| 6. | Team Lotus 🇬🇧 | 3 |
| 7. | Tyrrell 🇬🇧 | 3 |
| 8. | Alfa Romeo 🇮🇹 | 2 |
| 9. | Brabham 🇬🇧 | 2 |
| 10. | Lotus-Climax 🇬🇧 | 2 |
| 11. | Lotus-Ford 🇬🇧 | 2 |
| 12. | Maserati 🇮🇹 | 2 |
| 13. | Vanwall 🇬🇧 | 2 |
| 14. | Benetton 🇮🇹 | 1 |
| 15. | Brabham-Climax 🇬🇧 | 1 |
| 16. | BRM 🇬🇧 | 1 |
| 17. | Cooper-Climax 🇬🇧 | 1 |
| 18. | Cooper-Maserati 🇬🇧 | 1 |
| 19. | Honda 🇯🇵 | 1 |
| 20. | McLaren-Ford 🇬🇧 | 1 |
| 21. | Renault 🇫🇷 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
