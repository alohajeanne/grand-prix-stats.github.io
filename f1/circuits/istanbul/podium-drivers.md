---
title: Rank of Formula 1® Drivers by Number of Podiums at Istanbul Park
layout: page
rowCount: 9
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
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                4.0,
                3.0,
                3.0,
                3.0,
                2.0,
                2.0,
                2.0,
                1.0,
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Fernando Alonso",
        "Felipe Massa",
        "Kimi Räikkönen",
        "Mark Webber",
        "Jenson Button",
        "Lewis Hamilton",
        "Sebastian Vettel",
        "Juan Pablo Montoya",
        "Michael Schumacher"
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
| 1. | Fernando Alonso 🇪🇸 | 4 |
| 2. | Felipe Massa 🇧🇷 | 3 |
| 3. | Kimi Räikkönen 🇫🇮 | 3 |
| 4. | Mark Webber 🇦🇺 | 3 |
| 5. | Jenson Button 🇬🇧 | 2 |
| 6. | Lewis Hamilton 🇬🇧 | 2 |
| 7. | Sebastian Vettel 🇩🇪 | 2 |
| 8. | Juan Pablo Montoya 🇨🇴 | 1 |
| 9. | Michael Schumacher 🇩🇪 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
