---
title: Rank of Formula 1® Drivers by Number of Podiums at Montjuïc
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
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Jackie Stewart",
        "Jacky Ickx",
        "Bruce McLaren",
        "Carlos Reutemann",
        "Chris Amon",
        "Emerson Fittipaldi",
        "François Cevert",
        "George Follmer",
        "Jean-Pierre Beltoise",
        "Jochen Mass"
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
| 1. | Jackie Stewart 🇬🇧 | 2 |
| 2. | Jacky Ickx 🇧🇪 | 2 |
| 3. | Bruce McLaren 🇳🇿 | 1 |
| 4. | Carlos Reutemann 🇦🇷 | 1 |
| 5. | Chris Amon 🇳🇿 | 1 |
| 6. | Emerson Fittipaldi 🇧🇷 | 1 |
| 7. | François Cevert 🇫🇷 | 1 |
| 8. | George Follmer 🇺🇸 | 1 |
| 9. | Jean-Pierre Beltoise 🇫🇷 | 1 |
| 10. | Jochen Mass 🇩🇪 | 1 |

#### Statistic Summary

| **Row Count** | 10.000 |
| **Total Sum** | 12.000 |
| **Mean (Average)** | 1.200 |
| **Maximum** | 2.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.160 |
| **Standard Deviation** | 0.400 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
