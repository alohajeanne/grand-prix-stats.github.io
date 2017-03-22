---
title: Rank of Formula 1® Drivers by Number of Podiums at Dijon-Prenois
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
        "Niki Lauda",
        "Alain Prost",
        "John Watson",
        "Clay Regazzoni",
        "Gilles Villeneuve",
        "James Hunt",
        "Jean-Pierre Jabouille",
        "Keke Rosberg",
        "Mario Andretti",
        "Nelson Piquet",
        "Nigel Mansell",
        "Patrick Tambay",
        "René Arnoux",
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

| # | Driver | Number Of Podiums |
|--|--|--|
| 1. | Niki Lauda 🇦🇹 | 3 |
| 2. | Alain Prost 🇫🇷 | 2 |
| 3. | John Watson 🇬🇧 | 2 |
| 4. | Clay Regazzoni 🇨🇭 | 1 |
| 5. | Gilles Villeneuve 🇨🇦 | 1 |
| 6. | James Hunt 🇬🇧 | 1 |
| 7. | Jean-Pierre Jabouille 🇫🇷 | 1 |
| 8. | Keke Rosberg 🇫🇮 | 1 |
| 9. | Mario Andretti 🇺🇸 | 1 |
| 10. | Nelson Piquet 🇧🇷 | 1 |
| 11. | Nigel Mansell 🇬🇧 | 1 |
| 12. | Patrick Tambay 🇫🇷 | 1 |
| 13. | René Arnoux 🇫🇷 | 1 |
| 14. | Ronnie Peterson 🇸🇪 | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 14 |
| **Total Sum** | 18.000 |
| **Mean μ (Average)** | 1.286 |
| **Maximum** | 3.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.347 |
| **Standard Deviation σ** | 0.589 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
