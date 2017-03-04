---
title: List of All Formula 1® Drivers that Have Been in the Podium at Montjuïc
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
                2.0,
                1.0,
                1.0,
                1.0,
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
        "Jackie Stewart 🇬🇧",
        "Jacky Ickx 🇧🇪",
        "Bruce McLaren 🇳🇿",
        "Carlos Reutemann 🇦🇷",
        "Chris Amon 🇳🇿",
        "Emerson Fittipaldi 🇧🇷",
        "François Cevert 🇫🇷",
        "George Follmer 🇺🇸",
        "Jean-Pierre Beltoise 🇫🇷",
        "Jochen Mass 🇩🇪"
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
| 1. | Jackie Stewart 🇬🇧 | 2 |
| 2. | Jacky Ickx 🇧🇪 | 2 |
| 3. | Bruce McLaren 🇳🇿 | 1 |
| 4. | Carlos Reutemann 🇦🇷 | 1 |
| 5. | Chris Amon 🇳🇿 | 1 |
| 6. | Emerson Fittipaldi 🇧🇷 | 1 |
| 7. | François Cevert 🇫🇷 | 1 |
| 8. | George Follmer 🇺🇸 | 1 |
| 9. | Jean-Pierre Beltoise 🇫🇷 | 1 |
| 10. | Jochen Mass 🇩🇪 | 1 |

<small>Download Data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})</small>
