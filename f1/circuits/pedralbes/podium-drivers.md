---
title: List of All Formula 1® Drivers that Have Been in the Podium at Circuit de Pedralbes
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
        "Juan Fangio 🇦🇷",
        "José Froilán González 🇦🇷",
        "Luigi Musso 🇮🇹",
        "Mike Hawthorn 🇬🇧",
        "Nino Farina 🇮🇹"
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
| 1. | Juan Fangio 🇦🇷 | 2 |
| 2. | José Froilán González 🇦🇷 | 1 |
| 3. | Luigi Musso 🇮🇹 | 1 |
| 4. | Mike Hawthorn 🇬🇧 | 1 |
| 5. | Nino Farina 🇮🇹 | 1 |
