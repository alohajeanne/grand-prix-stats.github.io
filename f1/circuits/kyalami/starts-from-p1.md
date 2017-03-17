---
title: Rank of Formula 1® Drivers by Number of Starts from P1 at Kyalami
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
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
                2.0,
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
                1.0
            ],
            "label": "Number Of Starts From P1"
        }
    ],
    "labels": [
        "Jackie Stewart",
        "Jack Brabham",
        "James Hunt",
        "Jean-Pierre Jabouille",
        "Nigel Mansell",
        "Niki Lauda",
        "Alain Prost",
        "Carlos Pace",
        "Denny Hulme",
        "Jim Clark",
        "Nelson Piquet",
        "Patrick Tambay",
        "René Arnoux"
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
| 1. | Jackie Stewart 🇬🇧 | 3 |
| 2. | Jack Brabham 🇦🇺 | 2 |
| 3. | James Hunt 🇬🇧 | 2 |
| 4. | Jean-Pierre Jabouille 🇫🇷 | 2 |
| 5. | Nigel Mansell 🇬🇧 | 2 |
| 6. | Niki Lauda 🇦🇹 | 2 |
| 7. | Alain Prost 🇫🇷 | 1 |
| 8. | Carlos Pace 🇧🇷 | 1 |
| 9. | Denny Hulme 🇳🇿 | 1 |
| 10. | Jim Clark 🇬🇧 | 1 |
| 11. | Nelson Piquet 🇧🇷 | 1 |
| 12. | Patrick Tambay 🇫🇷 | 1 |
| 13. | René Arnoux 🇫🇷 | 1 |

#### Statistic Summary

| **Row Count** | 13.000 |
| **Total Sum** | 20.000 |
| **Mean (Average)** | 1.538 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.402 |
| **Standard Deviation** | 0.634 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
