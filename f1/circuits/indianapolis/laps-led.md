---
title: Rank of Formula 1® Drivers by Number of Laps Led at Indianapolis Motor Speedway
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
                338.0,
                67.0,
                66.0,
                31.0,
                30.0,
                18.0,
                15.0,
                7.0,
                5.0,
                2.0,
                2.0,
                2.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Rubens Barrichello",
        "Lewis Hamilton",
        "Mika Häkkinen",
        "Felipe Massa",
        "Kimi Räikkönen",
        "Jenson Button",
        "David Coulthard",
        "Heikki Kovalainen",
        "Fernando Alonso",
        "Juan Pablo Montoya",
        "Mark Webber",
        "Heinz-Harald Frentzen"
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
| 1. | Michael Schumacher 🇩🇪 | 338 |
| 2. | Rubens Barrichello 🇧🇷 | 67 |
| 3. | Lewis Hamilton 🇬🇧 | 66 |
| 4. | Mika Häkkinen 🇫🇮 | 31 |
| 5. | Felipe Massa 🇧🇷 | 30 |
| 6. | Kimi Räikkönen 🇫🇮 | 18 |
| 7. | Jenson Button 🇬🇧 | 15 |
| 8. | David Coulthard 🇬🇧 | 7 |
| 9. | Heikki Kovalainen 🇫🇮 | 5 |
| 10. | Fernando Alonso 🇪🇸 | 2 |
| 11. | Juan Pablo Montoya 🇨🇴 | 2 |
| 12. | Mark Webber 🇦🇺 | 2 |
| 13. | Heinz-Harald Frentzen 🇩🇪 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
