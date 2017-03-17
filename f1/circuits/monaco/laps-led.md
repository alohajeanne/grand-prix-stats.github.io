---
title: Rank of Formula 1® Drivers by Number of Laps Led at Circuit de Monaco
layout: page
rowCount: 20
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
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                282.0,
                170.0,
                167.0,
                153.0,
                140.0,
                101.0,
                93.0,
                85.0,
                78.0,
                76.0,
                74.0,
                40.0,
                38.0,
                24.0,
                23.0,
                21.0,
                20.0,
                16.0,
                10.0,
                5.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Nico Rosberg",
        "Lewis Hamilton",
        "Fernando Alonso",
        "Mark Webber",
        "David Coulthard",
        "Jenson Button",
        "Kimi Räikkönen",
        "Mika Häkkinen",
        "Sebastian Vettel",
        "Jarno Trulli",
        "Juan Pablo Montoya",
        "Damon Hill",
        "Daniel Ricciardo",
        "Felipe Massa",
        "Jean Alesi",
        "Ralf Schumacher",
        "Olivier Panis",
        "Robert Kubica",
        "Rubens Barrichello"
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

| # | Driver | Number Of Laps Led |
|--|--|--|
| 1. | Michael Schumacher 🇩🇪 | 282 |
| 2. | Nico Rosberg 🇩🇪 | 170 |
| 3. | Lewis Hamilton 🇬🇧 | 167 |
| 4. | Fernando Alonso 🇪🇸 | 153 |
| 5. | Mark Webber 🇦🇺 | 140 |
| 6. | David Coulthard 🇬🇧 | 101 |
| 7. | Jenson Button 🇬🇧 | 93 |
| 8. | Kimi Räikkönen 🇫🇮 | 85 |
| 9. | Mika Häkkinen 🇫🇮 | 78 |
| 10. | Sebastian Vettel 🇩🇪 | 76 |
| 11. | Jarno Trulli 🇮🇹 | 74 |
| 12. | Juan Pablo Montoya 🇨🇴 | 40 |
| 13. | Damon Hill 🇬🇧 | 38 |
| 14. | Daniel Ricciardo 🇦🇺 | 24 |
| 15. | Felipe Massa 🇧🇷 | 23 |
| 16. | Jean Alesi 🇫🇷 | 21 |
| 17. | Ralf Schumacher 🇩🇪 | 20 |
| 18. | Olivier Panis 🇫🇷 | 16 |
| 19. | Robert Kubica 🇵🇱 | 10 |
| 20. | Rubens Barrichello 🇧🇷 | 5 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
