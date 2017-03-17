---
title: Rank of Formula 1® Drivers by Number of Laps Led at Silverstone Circuit
layout: page
rowCount: 24
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
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                192.0,
                155.0,
                135.0,
                126.0,
                117.0,
                90.0,
                69.0,
                60.0,
                56.0,
                52.0,
                43.0,
                35.0,
                19.0,
                17.0,
                12.0,
                7.0,
                5.0,
                4.0,
                3.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Lewis Hamilton",
        "Fernando Alonso",
        "Mika Häkkinen",
        "Michael Schumacher",
        "Sebastian Vettel",
        "Jacques Villeneuve",
        "Juan Pablo Montoya",
        "Mark Webber",
        "Rubens Barrichello",
        "David Coulthard",
        "Kimi Räikkönen",
        "Nico Rosberg",
        "Felipe Massa",
        "Cristiano da Matta",
        "Jarno Trulli",
        "Jean Alesi",
        "Heinz-Harald Frentzen",
        "Heikki Kovalainen",
        "Giancarlo Fisichella",
        "Eddie Irvine",
        "Damon Hill",
        "Max Verstappen",
        "Nick Heidfeld",
        "Valtteri Bottas"
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
| 1. | Lewis Hamilton 🇬🇧 | 192 |
| 2. | Fernando Alonso 🇪🇸 | 155 |
| 3. | Mika Häkkinen 🇫🇮 | 135 |
| 4. | Michael Schumacher 🇩🇪 | 126 |
| 5. | Sebastian Vettel 🇩🇪 | 117 |
| 6. | Jacques Villeneuve 🇨🇦 | 90 |
| 7. | Juan Pablo Montoya 🇨🇴 | 69 |
| 8. | Mark Webber 🇦🇺 | 60 |
| 9. | Rubens Barrichello 🇧🇷 | 56 |
| 10. | David Coulthard 🇬🇧 | 52 |
| 11. | Kimi Räikkönen 🇫🇮 | 43 |
| 12. | Nico Rosberg 🇩🇪 | 35 |
| 13. | Felipe Massa 🇧🇷 | 19 |
| 14. | Cristiano da Matta 🇧🇷 | 17 |
| 15. | Jarno Trulli 🇮🇹 | 12 |
| 16. | Jean Alesi 🇫🇷 | 7 |
| 17. | Heinz-Harald Frentzen 🇩🇪 | 5 |
| 18. | Heikki Kovalainen 🇫🇮 | 4 |
| 19. | Giancarlo Fisichella 🇮🇹 | 3 |
| 20. | Eddie Irvine 🇬🇧 | 2 |
| 21. | Damon Hill 🇬🇧 | 1 |
| 22. | Max Verstappen 🇳🇱 | 1 |
| 23. | Nick Heidfeld 🇩🇪 | 1 |
| 24. | Valtteri Bottas 🇫🇮 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
