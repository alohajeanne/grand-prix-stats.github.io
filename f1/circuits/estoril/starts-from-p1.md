---
title: Rank of Formula 1® Drivers by Number of Starts from P1 at Autódromo do Estoril
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
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
                2.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Starts From P1"
        }
    ],
    "labels": [
        "Ayrton Senna",
        "Damon Hill",
        "Gerhard Berger",
        "Nigel Mansell",
        "Alain Prost",
        "David Coulthard",
        "Nelson Piquet",
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

| # | Driver | Number Of Starts From P1 |
|--|--|--|
| 1. | Ayrton Senna 🇧🇷 | 3 |
| 2. | Damon Hill 🇬🇧 | 2 |
| 3. | Gerhard Berger 🇦🇹 | 2 |
| 4. | Nigel Mansell 🇬🇧 | 2 |
| 5. | Alain Prost 🇫🇷 | 1 |
| 6. | David Coulthard 🇬🇧 | 1 |
| 7. | Nelson Piquet 🇧🇷 | 1 |
| 8. | Riccardo Patrese 🇮🇹 | 1 |

#### Statistic Summary

| **Row Count** | 8.000 |
| **Total Sum** | 13.000 |
| **Mean (Average)** | 1.625 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.484 |
| **Standard Deviation** | 0.696 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
