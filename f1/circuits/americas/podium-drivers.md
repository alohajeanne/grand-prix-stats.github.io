---
title: Rank of Formula 1® Drivers by Number of Podiums at Circuit of the Americas
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
                "#9C8E8D"
            ],
            "borderColor": [
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
                3.0,
                3.0,
                2.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Lewis Hamilton",
        "Nico Rosberg",
        "Sebastian Vettel",
        "Daniel Ricciardo",
        "Fernando Alonso",
        "Mark Webber",
        "Romain Grosjean"
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
| 1. | Lewis Hamilton 🇬🇧 | 4 |
| 2. | Nico Rosberg 🇩🇪 | 3 |
| 3. | Sebastian Vettel 🇩🇪 | 3 |
| 4. | Daniel Ricciardo 🇦🇺 | 2 |
| 5. | Fernando Alonso 🇪🇸 | 1 |
| 6. | Mark Webber 🇦🇺 | 1 |
| 7. | Romain Grosjean 🇫🇷 | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 7 |
| **Total Sum** | 15.000 |
| **Mean μ (Average)** | 2.143 |
| **Maximum** | 4.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.265 |
| **Standard Deviation σ** | 1.125 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
