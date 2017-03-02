---
title: List of All Formula 1® Drivers that Have Won a Race at Reims-Gueux
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
                2.0,
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
        "Juan Fangio 🇦🇷",
        "Jack Brabham 🇦🇺",
        "Mike Hawthorn 🇬🇧",
        "Giancarlo Baghetti 🇮🇹",
        "Jim Clark 🇬🇧",
        "Luigi Fagioli 🇮🇹",
        "Peter Collins 🇬🇧",
        "Tony Brooks 🇬🇧"
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
new Chart("chart", {
    data: data,
    type: 'bar',
    options: options
});
</script>



#### Data Table

| # | Driver | Times |
|--|--|--|
| 1. | Juan Fangio 🇦🇷 | 3 |
| 2. | Jack Brabham 🇦🇺 | 2 |
| 3. | Mike Hawthorn 🇬🇧 | 2 |
| 4. | Giancarlo Baghetti 🇮🇹 | 1 |
| 5. | Jim Clark 🇬🇧 | 1 |
| 6. | Luigi Fagioli 🇮🇹 | 1 |
| 7. | Peter Collins 🇬🇧 | 1 |
| 8. | Tony Brooks 🇬🇧 | 1 |
