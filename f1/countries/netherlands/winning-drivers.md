---
title: List of All Formula 1® Drivers that Have Won a Race in Netherlands by Number of Times
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
                4.0,
                3.0,
                3.0,
                2.0,
                2.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
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
            "label": "Times"
        }
    ],
    "labels": [
        "Jim Clark",
        "Jackie Stewart",
        "Niki Lauda",
        "Alain Prost",
        "Alberto Ascari",
        "Jack Brabham",
        "James Hunt",
        "Alan Jones",
        "Didier Pironi",
        "Graham Hill",
        "Jacky Ickx",
        "Jo Bonnier",
        "Jochen Rindt",
        "Juan Fangio",
        "Mario Andretti",
        "Nelson Piquet",
        "René Arnoux",
        "Stirling Moss",
        "Wolfgang von Trips"
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
| 1. | Jim Clark 🇬🇧 | 4 |
| 2. | Jackie Stewart 🇬🇧 | 3 |
| 3. | Niki Lauda 🇦🇹 | 3 |
| 4. | Alain Prost 🇫🇷 | 2 |
| 5. | Alberto Ascari 🇮🇹 | 2 |
| 6. | Jack Brabham 🇦🇺 | 2 |
| 7. | James Hunt 🇬🇧 | 2 |
| 8. | Alan Jones 🇦🇺 | 1 |
| 9. | Didier Pironi 🇫🇷 | 1 |
| 10. | Graham Hill 🇬🇧 | 1 |
| 11. | Jacky Ickx 🇧🇪 | 1 |
| 12. | Jo Bonnier 🇸🇪 | 1 |
| 13. | Jochen Rindt 🇦🇹 | 1 |
| 14. | Juan Fangio 🇦🇷 | 1 |
| 15. | Mario Andretti 🇺🇸 | 1 |
| 16. | Nelson Piquet 🇧🇷 | 1 |
| 17. | René Arnoux 🇫🇷 | 1 |
| 18. | Stirling Moss 🇬🇧 | 1 |
| 19. | Wolfgang von Trips 🇩🇪 | 1 |

#### Statistic Summary

| **Row Count** | 19.000 |
| **Total Sum** | 30.000 |
| **Mean (Average)** | 1.579 |
| **Maximum** | 4.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.770 |
| **Standard Deviation** | 0.878 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
