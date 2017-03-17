---
title: Rank of Formula 1® Drivers by Number of Podiums at Sochi International Street Circuit
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
                "#f3a935"
            ],
            "borderColor": [
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
                2.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Lewis Hamilton",
        "Nico Rosberg",
        "Kimi Räikkönen",
        "Sebastian Vettel",
        "Sergio Pérez",
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



### Data Table

| # | Driver | Number Of Podiums |
|--|--|--|
| 1. | Lewis Hamilton 🇬🇧 | 3 |
| 2. | Nico Rosberg 🇩🇪 | 2 |
| 3. | Kimi Räikkönen 🇫🇮 | 1 |
| 4. | Sebastian Vettel 🇩🇪 | 1 |
| 5. | Sergio Pérez 🇲🇽 | 1 |
| 6. | Valtteri Bottas 🇫🇮 | 1 |

#### Statistic Summary

| **Row Count** | 6.000 |
| **Total Sum** | 9.000 |
| **Mean (Average)** | 1.500 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.583 |
| **Standard Deviation** | 0.764 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
