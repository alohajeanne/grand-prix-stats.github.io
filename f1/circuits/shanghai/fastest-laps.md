---
title: Rank of Formula 1® Drivers by Number of Fastest Laps at Shanghai International Circuit
layout: page
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
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
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
            "label": "Number Of Fastest Laps"
        }
    ],
    "labels": [
        "Lewis Hamilton",
        "Felipe Massa",
        "Fernando Alonso",
        "Kamui Kobayashi",
        "Kimi Räikkönen",
        "Michael Schumacher",
        "Nico Hülkenberg",
        "Nico Rosberg",
        "Rubens Barrichello",
        "Sebastian Vettel"
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



### Data Table

| # | Driver | Number Of Fastest Laps |
|--|--|--|
| 1. | Lewis Hamilton 🇬🇧 | 3 |
| 2. | Felipe Massa 🇧🇷 | 1 |
| 3. | Fernando Alonso 🇪🇸 | 1 |
| 4. | Kamui Kobayashi 🇯🇵 | 1 |
| 5. | Kimi Räikkönen 🇫🇮 | 1 |
| 6. | Michael Schumacher 🇩🇪 | 1 |
| 7. | Nico Hülkenberg 🇩🇪 | 1 |
| 8. | Nico Rosberg 🇩🇪 | 1 |
| 9. | Rubens Barrichello 🇧🇷 | 1 |
| 10. | Sebastian Vettel 🇩🇪 | 1 |

#### Statistic Summary

| **Row Count** | 10.000 |
| **Total Sum** | 12.000 |
| **Mean (Average)** | 1.200 |
| **Maximum** | 3.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.360 |
| **Standard Deviation** | 0.600 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
