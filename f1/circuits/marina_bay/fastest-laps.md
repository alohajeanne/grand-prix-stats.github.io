---
title: Rank of Formula 1® Drivers by Number of Fastest Laps at Marina Bay Street Circuit
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
                "#f3a935"
            ],
            "borderColor": [
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
                2.0,
                2.0,
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
        "Daniel Ricciardo",
        "Fernando Alonso",
        "Jenson Button",
        "Kimi Räikkönen",
        "Lewis Hamilton",
        "Nico Hülkenberg",
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
| 1. | Daniel Ricciardo 🇦🇺 | 2 |
| 2. | Fernando Alonso 🇪🇸 | 2 |
| 3. | Jenson Button 🇬🇧 | 1 |
| 4. | Kimi Räikkönen 🇫🇮 | 1 |
| 5. | Lewis Hamilton 🇬🇧 | 1 |
| 6. | Nico Hülkenberg 🇩🇪 | 1 |
| 7. | Sebastian Vettel 🇩🇪 | 1 |

#### Statistic Summary

| **Row Count** | 7.000 |
| **Total Sum** | 9.000 |
| **Mean (Average)** | 1.286 |
| **Maximum** | 2.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.204 |
| **Standard Deviation** | 0.452 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
