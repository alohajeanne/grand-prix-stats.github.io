---
title: List of All Formula 1® Drivers that Have Won a Race in Argentina by Number of Times
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
                4.0,
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
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Juan Fangio",
        "Damon Hill",
        "Emerson Fittipaldi",
        "Alan Jones",
        "Alberto Ascari",
        "Bruce McLaren",
        "Denny Hulme",
        "Jackie Stewart",
        "Jacques Laffite",
        "Jacques Villeneuve",
        "Jody Scheckter",
        "Luigi Musso",
        "Mario Andretti",
        "Michael Schumacher",
        "Nelson Piquet",
        "Stirling Moss"
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
| 1. | Juan Fangio 🇦🇷 | 4 |
| 2. | Damon Hill 🇬🇧 | 2 |
| 3. | Emerson Fittipaldi 🇧🇷 | 2 |
| 4. | Alan Jones 🇦🇺 | 1 |
| 5. | Alberto Ascari 🇮🇹 | 1 |
| 6. | Bruce McLaren 🇳🇿 | 1 |
| 7. | Denny Hulme 🇳🇿 | 1 |
| 8. | Jackie Stewart 🇬🇧 | 1 |
| 9. | Jacques Laffite 🇫🇷 | 1 |
| 10. | Jacques Villeneuve 🇨🇦 | 1 |
| 11. | Jody Scheckter 🇿🇦 | 1 |
| 12. | Luigi Musso 🇮🇹 | 1 |
| 13. | Mario Andretti 🇺🇸 | 1 |
| 14. | Michael Schumacher 🇩🇪 | 1 |
| 15. | Nelson Piquet 🇧🇷 | 1 |
| 16. | Stirling Moss 🇬🇧 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 16 |
| **Total Sum** | 21.000 |
| **Mean μ (Average)** | 1.312 |
| **Maximum** | 4.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.590 |
| **Standard Deviation σ** | 0.768 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
