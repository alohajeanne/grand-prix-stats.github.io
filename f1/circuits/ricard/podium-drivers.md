---
title: Rank of Formula 1® Drivers by Number of Podiums at Circuit Paul Ricard
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
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                8.0,
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
        "Alain Prost",
        "Nelson Piquet",
        "James Hunt",
        "Nigel Mansell",
        "Ayrton Senna",
        "Didier Pironi",
        "François Cevert",
        "Ronnie Peterson",
        "Alan Jones",
        "Carlos Reutemann",
        "Eddie Cheever",
        "Emerson Fittipaldi",
        "Ivan Capelli",
        "Jackie Stewart",
        "Jacques Laffite",
        "Jochen Mass",
        "John Watson",
        "Keke Rosberg",
        "Mario Andretti",
        "Michele Alboreto",
        "Niki Lauda",
        "Patrick Depailler",
        "René Arnoux",
        "Riccardo Patrese"
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
| 1. | Alain Prost 🇫🇷 | 8 |
| 2. | Nelson Piquet 🇧🇷 | 4 |
| 3. | James Hunt 🇬🇧 | 3 |
| 4. | Nigel Mansell 🇬🇧 | 3 |
| 5. | Ayrton Senna 🇧🇷 | 2 |
| 6. | Didier Pironi 🇫🇷 | 2 |
| 7. | François Cevert 🇫🇷 | 2 |
| 8. | Ronnie Peterson 🇸🇪 | 2 |
| 9. | Alan Jones 🇦🇺 | 1 |
| 10. | Carlos Reutemann 🇦🇷 | 1 |
| 11. | Eddie Cheever 🇺🇸 | 1 |
| 12. | Emerson Fittipaldi 🇧🇷 | 1 |
| 13. | Ivan Capelli 🇮🇹 | 1 |
| 14. | Jackie Stewart 🇬🇧 | 1 |
| 15. | Jacques Laffite 🇫🇷 | 1 |
| 16. | Jochen Mass 🇩🇪 | 1 |
| 17. | John Watson 🇬🇧 | 1 |
| 18. | Keke Rosberg 🇫🇮 | 1 |
| 19. | Mario Andretti 🇺🇸 | 1 |
| 20. | Michele Alboreto 🇮🇹 | 1 |
| 21. | Niki Lauda 🇦🇹 | 1 |
| 22. | Patrick Depailler 🇫🇷 | 1 |
| 23. | René Arnoux 🇫🇷 | 1 |
| 24. | Riccardo Patrese 🇮🇹 | 1 |

#### Statistic Summary

| **Row Count** | 24.000 |
| **Total Sum** | 42.000 |
| **Mean (Average)** | 1.750 |
| **Maximum** | 8.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 2.354 |
| **Standard Deviation** | 1.534 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
