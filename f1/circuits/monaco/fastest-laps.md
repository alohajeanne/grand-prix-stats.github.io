---
title: Rank of Formula 1® Drivers by Number of Fastest Laps at Circuit de Monaco
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
                3.0,
                2.0,
                2.0,
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
        "Michael Schumacher",
        "Kimi Räikkönen",
        "Sebastian Vettel",
        "Daniel Ricciardo",
        "Felipe Massa",
        "Fernando Alonso",
        "Lewis Hamilton",
        "Mark Webber",
        "Sergio Pérez"
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
| 1. | Michael Schumacher 🇩🇪 | 3 |
| 2. | Kimi Räikkönen 🇫🇮 | 2 |
| 3. | Sebastian Vettel 🇩🇪 | 2 |
| 4. | Daniel Ricciardo 🇦🇺 | 1 |
| 5. | Felipe Massa 🇧🇷 | 1 |
| 6. | Fernando Alonso 🇪🇸 | 1 |
| 7. | Lewis Hamilton 🇬🇧 | 1 |
| 8. | Mark Webber 🇦🇺 | 1 |
| 9. | Sergio Pérez 🇲🇽 | 1 |

#### Statistic Summary

| **Row Count** | 9.000 |
| **Total Sum** | 13.000 |
| **Mean (Average)** | 1.444 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.469 |
| **Standard Deviation** | 0.685 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
