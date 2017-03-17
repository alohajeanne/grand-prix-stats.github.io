---
title: Rank of Formula 1® Drivers by Number of Laps Led at Circuit de Catalunya
layout: page
rowCount: 21
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
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                319.0,
                177.0,
                149.0,
                137.0,
                84.0,
                76.0,
                73.0,
                66.0,
                56.0,
                45.0,
                41.0,
                37.0,
                33.0,
                30.0,
                30.0,
                8.0,
                6.0,
                5.0,
                2.0,
                1.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Mika Häkkinen",
        "Fernando Alonso",
        "Kimi Räikkönen",
        "Lewis Hamilton",
        "Nico Rosberg",
        "Jacques Villeneuve",
        "Mark Webber",
        "Felipe Massa",
        "Sebastian Vettel",
        "Rubens Barrichello",
        "Pastor Maldonado",
        "Jenson Button",
        "Daniel Ricciardo",
        "Max Verstappen",
        "Jarno Trulli",
        "David Coulthard",
        "Nick Heidfeld",
        "Esteban Gutiérrez",
        "Giancarlo Fisichella",
        "Jean Alesi"
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
| 1. | Michael Schumacher 🇩🇪 | 319 |
| 2. | Mika Häkkinen 🇫🇮 | 177 |
| 3. | Fernando Alonso 🇪🇸 | 149 |
| 4. | Kimi Räikkönen 🇫🇮 | 137 |
| 5. | Lewis Hamilton 🇬🇧 | 84 |
| 6. | Nico Rosberg 🇩🇪 | 76 |
| 7. | Jacques Villeneuve 🇨🇦 | 73 |
| 8. | Mark Webber 🇦🇺 | 66 |
| 9. | Felipe Massa 🇧🇷 | 56 |
| 10. | Sebastian Vettel 🇩🇪 | 45 |
| 11. | Rubens Barrichello 🇧🇷 | 41 |
| 12. | Pastor Maldonado 🇻🇪 | 37 |
| 13. | Jenson Button 🇬🇧 | 33 |
| 14. | Daniel Ricciardo 🇦🇺 | 30 |
| 15. | Max Verstappen 🇳🇱 | 30 |
| 16. | Jarno Trulli 🇮🇹 | 8 |
| 17. | David Coulthard 🇬🇧 | 6 |
| 18. | Nick Heidfeld 🇩🇪 | 5 |
| 19. | Esteban Gutiérrez 🇲🇽 | 2 |
| 20. | Giancarlo Fisichella 🇮🇹 | 1 |
| 21. | Jean Alesi 🇫🇷 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
