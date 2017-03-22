---
title: List of All Formula 1® Drivers that Have Won a Race in Turkey by Number of Times
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
                "#9C8E8D"
            ],
            "borderColor": [
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Felipe Massa",
        "Jenson Button",
        "Kimi Räikkönen",
        "Lewis Hamilton",
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

| # | Driver | Times |
|--|--|--|
| 1. | Felipe Massa 🇧🇷 | 3 |
| 2. | Jenson Button 🇬🇧 | 1 |
| 3. | Kimi Räikkönen 🇫🇮 | 1 |
| 4. | Lewis Hamilton 🇬🇧 | 1 |
| 5. | Sebastian Vettel 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 5 |
| **Total Sum** | 7.000 |
| **Mean μ (Average)** | 1.400 |
| **Maximum** | 3.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.640 |
| **Standard Deviation σ** | 0.800 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
