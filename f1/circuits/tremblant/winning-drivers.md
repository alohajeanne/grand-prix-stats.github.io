---
title: List of All Formula 1® Drivers that Have Won a Race at Circuit Mont-Tremblant
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
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Denny Hulme 🇳🇿",
        "Jacky Ickx 🇧🇪"
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
| 1. | Denny Hulme 🇳🇿 | 1 |
| 2. | Jacky Ickx 🇧🇪 | 1 |
