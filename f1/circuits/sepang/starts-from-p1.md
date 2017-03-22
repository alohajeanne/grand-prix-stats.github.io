---
title: Rank of Formula 1® Drivers by Number of Starts from P1 at Sepang International Circuit
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
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                5.0,
                4.0,
                2.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Starts From P1"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Lewis Hamilton",
        "Felipe Massa",
        "Fernando Alonso",
        "Sebastian Vettel",
        "Giancarlo Fisichella",
        "Jenson Button",
        "Mark Webber"
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
| 1. | Michael Schumacher 🇩🇪 | 5 |
| 2. | Lewis Hamilton 🇬🇧 | 4 |
| 3. | Felipe Massa 🇧🇷 | 2 |
| 4. | Fernando Alonso 🇪🇸 | 2 |
| 5. | Sebastian Vettel 🇩🇪 | 2 |
| 6. | Giancarlo Fisichella 🇮🇹 | 1 |
| 7. | Jenson Button 🇬🇧 | 1 |
| 8. | Mark Webber 🇦🇺 | 1 |

#### Statistic Summary

| **Column** | **Number Of Starts From P1** |
| **Row Count** | 8 |
| **Total Sum** | 18.000 |
| **Mean μ (Average)** | 2.250 |
| **Maximum** | 5.000 |
| **75th Percentile** | 4.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.938 |
| **Standard Deviation σ** | 1.392 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})