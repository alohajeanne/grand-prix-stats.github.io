---
title: List of All Formula 1® Drivers that Have Been in the Podium at Buddh International Circuit
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
                3.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Sebastian Vettel 🇩🇪",
        "Fernando Alonso 🇪🇸",
        "Jenson Button 🇬🇧",
        "Mark Webber 🇦🇺",
        "Nico Rosberg 🇩🇪",
        "Romain Grosjean 🇫🇷"
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
| 1. | Sebastian Vettel 🇩🇪 | 3 |
| 2. | Fernando Alonso 🇪🇸 | 2 |
| 3. | Jenson Button 🇬🇧 | 1 |
| 4. | Mark Webber 🇦🇺 | 1 |
| 5. | Nico Rosberg 🇩🇪 | 1 |
| 6. | Romain Grosjean 🇫🇷 | 1 |
