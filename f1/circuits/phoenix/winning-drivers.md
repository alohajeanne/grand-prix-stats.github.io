---
title: Rank of Formula 1® Drivers by Number of Wins at Phoenix street circuit
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "#9C8E8D",
                "#9C8E8D"
            ],
            "borderColor": [
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                2.0,
                1.0
            ],
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "Ayrton Senna",
        "Alain Prost"
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

| # | Driver | Number Of Wins |
|--|--|--|
| 1. | Ayrton Senna 🇧🇷 | 2 |
| 2. | Alain Prost 🇫🇷 | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 2 |
| **Total Sum** | 3.000 |
| **Mean μ (Average)** | 1.500 |
| **Maximum** | 2.000 |
| **75th Percentile** | 2.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.250 |
| **Standard Deviation σ** | 0.500 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
