---
title: Rank of Formula 1® Drivers by Number of Laps Led at Autodromo Nazionale di Monza
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
                205.0,
                149.0,
                147.0,
                104.0,
                84.0,
                78.0,
                78.0,
                59.0,
                56.0,
                44.0,
                28.0,
                26.0,
                23.0,
                10.0,
                5.0,
                5.0,
                5.0,
                4.0,
                2.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Lewis Hamilton",
        "Sebastian Vettel",
        "Rubens Barrichello",
        "Juan Pablo Montoya",
        "Fernando Alonso",
        "Nico Rosberg",
        "Jenson Button",
        "Jean Alesi",
        "Mika Häkkinen",
        "David Coulthard",
        "Kimi Räikkönen",
        "Heinz-Harald Frentzen",
        "Ralf Schumacher",
        "Damon Hill",
        "Robert Kubica",
        "Sergio Pérez",
        "Heikki Kovalainen",
        "Felipe Massa",
        "Mika Salo"
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
| 1. | Michael Schumacher 🇩🇪 | 205 |
| 2. | Lewis Hamilton 🇬🇧 | 149 |
| 3. | Sebastian Vettel 🇩🇪 | 147 |
| 4. | Rubens Barrichello 🇧🇷 | 104 |
| 5. | Juan Pablo Montoya 🇨🇴 | 84 |
| 6. | Fernando Alonso 🇪🇸 | 78 |
| 7. | Nico Rosberg 🇩🇪 | 78 |
| 8. | Jenson Button 🇬🇧 | 59 |
| 9. | Jean Alesi 🇫🇷 | 56 |
| 10. | Mika Häkkinen 🇫🇮 | 44 |
| 11. | David Coulthard 🇬🇧 | 28 |
| 12. | Kimi Räikkönen 🇫🇮 | 26 |
| 13. | Heinz-Harald Frentzen 🇩🇪 | 23 |
| 14. | Ralf Schumacher 🇩🇪 | 10 |
| 15. | Damon Hill 🇬🇧 | 5 |
| 16. | Robert Kubica 🇵🇱 | 5 |
| 17. | Sergio Pérez 🇲🇽 | 5 |
| 18. | Heikki Kovalainen 🇫🇮 | 4 |
| 19. | Felipe Massa 🇧🇷 | 2 |
| 20. | Mika Salo 🇫🇮 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
