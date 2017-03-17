---
title: Rank of Formula 1® Drivers by Number of Laps Led at Yas Marina Circuit
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
                181.0,
                142.0,
                47.0,
                36.0,
                15.0,
                14.0,
                3.0,
                1.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Lewis Hamilton",
        "Sebastian Vettel",
        "Nico Rosberg",
        "Kimi Räikkönen",
        "Jenson Button",
        "Felipe Massa",
        "Fernando Alonso",
        "Daniel Ricciardo",
        "Mark Webber"
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
| 1. | Lewis Hamilton 🇬🇧 | 181 |
| 2. | Sebastian Vettel 🇩🇪 | 142 |
| 3. | Nico Rosberg 🇩🇪 | 47 |
| 4. | Kimi Räikkönen 🇫🇮 | 36 |
| 5. | Jenson Button 🇬🇧 | 15 |
| 6. | Felipe Massa 🇧🇷 | 14 |
| 7. | Fernando Alonso 🇪🇸 | 3 |
| 8. | Daniel Ricciardo 🇦🇺 | 1 |
| 9. | Mark Webber 🇦🇺 | 1 |

#### Table Summary

|**Row Count**|{{ page.rowCount }}|
|**Download**|[json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})|
