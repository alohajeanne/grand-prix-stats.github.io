---
title: Rank of Formula 1® Drivers by Number of Laps Led at Circuito de Jerez
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D"
            ],
            "borderColor": [
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                39.0,
                24.0,
                5.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Jacques Villeneuve",
        "Heinz-Harald Frentzen",
        "Mika Häkkinen"
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

| # | Driver | Number Of Laps Led |
|--|--|--|
| 1. | Michael Schumacher 🇩🇪 | 39 |
| 2. | Jacques Villeneuve 🇨🇦 | 24 |
| 3. | Heinz-Harald Frentzen 🇩🇪 | 5 |
| 4. | Mika Häkkinen 🇫🇮 | 1 |

#### Statistic Summary

| **Column** | **Number Of Laps Led** |
| **Row Count** | 4 |
| **Total Sum** | 69.000 |
| **Mean μ (Average)** | 17.250 |
| **Maximum** | 39.000 |
| **75th Percentile** | 39.000 |
| **Median** | 24.000 |
| **25th Percentile** | 5.000 |
| **Minimum** | 1.000 |
| **Variance** | 233.188 |
| **Standard Deviation σ** | 15.270 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
