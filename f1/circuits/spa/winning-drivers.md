---
title: Rank of Formula 1® Drivers by Number of Wins at Circuit de Spa-Francorchamps
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
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                6.0,
                5.0,
                4.0,
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
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Ayrton Senna",
        "Jim Clark",
        "Kimi Räikkönen",
        "Damon Hill",
        "Juan Fangio",
        "Alain Prost",
        "Alberto Ascari",
        "Lewis Hamilton",
        "Sebastian Vettel",
        "Bruce McLaren",
        "Dan Gurney",
        "Daniel Ricciardo",
        "David Coulthard",
        "Felipe Massa",
        "Jack Brabham",
        "Jenson Button",
        "John Surtees",
        "Mika Häkkinen",
        "Nico Rosberg",
        "Nigel Mansell",
        "Nino Farina",
        "Pedro Rodríguez",
        "Peter Collins",
        "Phil Hill",
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
| 1. | Michael Schumacher 🇩🇪 | 6 |
| 2. | Ayrton Senna 🇧🇷 | 5 |
| 3. | Jim Clark 🇬🇧 | 4 |
| 4. | Kimi Räikkönen 🇫🇮 | 4 |
| 5. | Damon Hill 🇬🇧 | 3 |
| 6. | Juan Fangio 🇦🇷 | 3 |
| 7. | Alain Prost 🇫🇷 | 2 |
| 8. | Alberto Ascari 🇮🇹 | 2 |
| 9. | Lewis Hamilton 🇬🇧 | 2 |
| 10. | Sebastian Vettel 🇩🇪 | 2 |
| 11. | Bruce McLaren 🇳🇿 | 1 |
| 12. | Dan Gurney 🇺🇸 | 1 |
| 13. | Daniel Ricciardo 🇦🇺 | 1 |
| 14. | David Coulthard 🇬🇧 | 1 |
| 15. | Felipe Massa 🇧🇷 | 1 |
| 16. | Jack Brabham 🇦🇺 | 1 |
| 17. | Jenson Button 🇬🇧 | 1 |
| 18. | John Surtees 🇬🇧 | 1 |
| 19. | Mika Häkkinen 🇫🇮 | 1 |
| 20. | Nico Rosberg 🇩🇪 | 1 |
| 21. | Nigel Mansell 🇬🇧 | 1 |
| 22. | Nino Farina 🇮🇹 | 1 |
| 23. | Pedro Rodríguez 🇲🇽 | 1 |
| 24. | Peter Collins 🇬🇧 | 1 |
| 25. | Phil Hill 🇺🇸 | 1 |
| 26. | Tony Brooks 🇬🇧 | 1 |

#### Statistic Summary

| **Row Count** | 26.000 |
| **Total Sum** | 49.000 |
| **Mean (Average)** | 1.885 |
| **Maximum** | 6.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.948 |
| **Standard Deviation** | 1.396 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
