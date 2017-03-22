---
title: List of All Formula 1® Drivers that Have Won a Race in South Africa by Number of Times
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
                "#9C8E8D",
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
                "#1D181E",
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
                3.0,
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
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Jim Clark",
        "Niki Lauda",
        "Alain Prost",
        "Jackie Stewart",
        "Nigel Mansell",
        "Carlos Reutemann",
        "Denny Hulme",
        "Gilles Villeneuve",
        "Graham Hill",
        "Jack Brabham",
        "Jody Scheckter",
        "Mario Andretti",
        "Pedro Rodríguez",
        "René Arnoux",
        "Riccardo Patrese",
        "Ronnie Peterson"
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
| 1. | Jim Clark 🇬🇧 | 3 |
| 2. | Niki Lauda 🇦🇹 | 3 |
| 3. | Alain Prost 🇫🇷 | 2 |
| 4. | Jackie Stewart 🇬🇧 | 2 |
| 5. | Nigel Mansell 🇬🇧 | 2 |
| 6. | Carlos Reutemann 🇦🇷 | 1 |
| 7. | Denny Hulme 🇳🇿 | 1 |
| 8. | Gilles Villeneuve 🇨🇦 | 1 |
| 9. | Graham Hill 🇬🇧 | 1 |
| 10. | Jack Brabham 🇦🇺 | 1 |
| 11. | Jody Scheckter 🇿🇦 | 1 |
| 12. | Mario Andretti 🇺🇸 | 1 |
| 13. | Pedro Rodríguez 🇲🇽 | 1 |
| 14. | René Arnoux 🇫🇷 | 1 |
| 15. | Riccardo Patrese 🇮🇹 | 1 |
| 16. | Ronnie Peterson 🇸🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 16 |
| **Total Sum** | 23.000 |
| **Mean μ (Average)** | 1.438 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.496 |
| **Standard Deviation σ** | 0.704 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
