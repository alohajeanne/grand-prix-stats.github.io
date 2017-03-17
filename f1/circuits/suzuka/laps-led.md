---
title: Rank of Formula 1® Drivers by Number of Laps Led at Suzuka Circuit
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
                238.0,
                188.0,
                134.0,
                74.0,
                71.0,
                52.0,
                50.0,
                41.0,
                27.0,
                26.0,
                19.0,
                17.0,
                14.0,
                13.0,
                7.0,
                6.0,
                6.0,
                5.0,
                4.0,
                3.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Sebastian Vettel",
        "Mika Häkkinen",
        "Nico Rosberg",
        "Lewis Hamilton",
        "Damon Hill",
        "Jenson Button",
        "Rubens Barrichello",
        "Giancarlo Fisichella",
        "Romain Grosjean",
        "Fernando Alonso",
        "Eddie Irvine",
        "Ralf Schumacher",
        "Juan Pablo Montoya",
        "Kimi Räikkönen",
        "Jacques Villeneuve",
        "Mark Webber",
        "Heinz-Harald Frentzen",
        "Felipe Massa",
        "David Coulthard"
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
| 1. | Michael Schumacher 🇩🇪 | 238 |
| 2. | Sebastian Vettel 🇩🇪 | 188 |
| 3. | Mika Häkkinen 🇫🇮 | 134 |
| 4. | Nico Rosberg 🇩🇪 | 74 |
| 5. | Lewis Hamilton 🇬🇧 | 71 |
| 6. | Damon Hill 🇬🇧 | 52 |
| 7. | Jenson Button 🇬🇧 | 50 |
| 8. | Rubens Barrichello 🇧🇷 | 41 |
| 9. | Giancarlo Fisichella 🇮🇹 | 27 |
| 10. | Romain Grosjean 🇫🇷 | 26 |
| 11. | Fernando Alonso 🇪🇸 | 19 |
| 12. | Eddie Irvine 🇬🇧 | 17 |
| 13. | Ralf Schumacher 🇩🇪 | 14 |
| 14. | Juan Pablo Montoya 🇨🇴 | 13 |
| 15. | Kimi Räikkönen 🇫🇮 | 7 |
| 16. | Jacques Villeneuve 🇨🇦 | 6 |
| 17. | Mark Webber 🇦🇺 | 6 |
| 18. | Heinz-Harald Frentzen 🇩🇪 | 5 |
| 19. | Felipe Massa 🇧🇷 | 4 |
| 20. | David Coulthard 🇬🇧 | 3 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
