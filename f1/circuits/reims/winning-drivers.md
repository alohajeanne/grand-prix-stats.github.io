---
title: Rank of Formula 1® Drivers by Number of Wins at Reims-Gueux
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
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D"
            ],
            "borderColor": [
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "Juan Fangio",
        "Jack Brabham",
        "Mike Hawthorn",
        "Giancarlo Baghetti",
        "Jim Clark",
        "Luigi Fagioli",
        "Peter Collins",
        "Tony Brooks"
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
| 1. | Juan Fangio 🇦🇷 | 3 |
| 2. | Jack Brabham 🇦🇺 | 2 |
| 3. | Mike Hawthorn 🇬🇧 | 2 |
| 4. | Giancarlo Baghetti 🇮🇹 | 1 |
| 5. | Jim Clark 🇬🇧 | 1 |
| 6. | Luigi Fagioli 🇮🇹 | 1 |
| 7. | Peter Collins 🇬🇧 | 1 |
| 8. | Tony Brooks 🇬🇧 | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 8 |
| **Total Sum** | 12.000 |
| **Mean μ (Average)** | 1.500 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.500 |
| **Standard Deviation σ** | 0.707 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
