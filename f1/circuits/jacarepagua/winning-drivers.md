---
title: List of All Formula 1® Drivers that Have Won a Race at Autódromo Internacional Nelson Piquet
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
                5.0,
                2.0,
                2.0,
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Alain Prost 🇫🇷",
        "Carlos Reutemann 🇦🇷",
        "Nelson Piquet 🇧🇷",
        "Nigel Mansell 🇬🇧"
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
| 1. | Alain Prost 🇫🇷 | 5 |
| 2. | Carlos Reutemann 🇦🇷 | 2 |
| 3. | Nelson Piquet 🇧🇷 | 2 |
| 4. | Nigel Mansell 🇬🇧 | 1 |
