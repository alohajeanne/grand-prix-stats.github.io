---
title: List of All Formula 1® Drivers that Have Been in the Podium at Riverside International Raceway
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": "#f3a935",
            "borderColor": "#f68639",
            "borderWidth": 1,
            "data": [
                1.0,
                1.0,
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Bruce McLaren 🇳🇿",
        "Innes Ireland 🇬🇧",
        "Stirling Moss 🇬🇧"
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
        maxRotation: 180
      }
    }],
    yAxes: [{
      ticks: {
        beginAtZero: true
      }
    }]
  }
};
new Chart("chart", {
    data: data,
    type: 'bar',
    options: options
});
</script>



#### Data Table

| # | Driver | Times |
|--|--|--|
| 1. | Bruce McLaren 🇳🇿 | 1 |
| 2. | Innes Ireland 🇬🇧 | 1 |
| 3. | Stirling Moss 🇬🇧 | 1 |
