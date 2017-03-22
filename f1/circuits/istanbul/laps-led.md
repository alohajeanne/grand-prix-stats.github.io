---
title: Rank of Formula 1® Drivers by Number of Laps Led at Istanbul Park
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
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                151.0,
                63.0,
                61.0,
                57.0,
                38.0,
                30.0,
                4.0,
                1.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Felipe Massa",
        "Kimi Räikkönen",
        "Jenson Button",
        "Sebastian Vettel",
        "Mark Webber",
        "Lewis Hamilton",
        "Michael Schumacher",
        "Fernando Alonso",
        "Heikki Kovalainen"
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

| # | Driver | Number Of Laps Led |
|--|--|--|
| 1. | Felipe Massa 🇧🇷 | 151 |
| 2. | Kimi Räikkönen 🇫🇮 | 63 |
| 3. | Jenson Button 🇬🇧 | 61 |
| 4. | Sebastian Vettel 🇩🇪 | 57 |
| 5. | Mark Webber 🇦🇺 | 38 |
| 6. | Lewis Hamilton 🇬🇧 | 30 |
| 7. | Michael Schumacher 🇩🇪 | 4 |
| 8. | Fernando Alonso 🇪🇸 | 1 |
| 9. | Heikki Kovalainen 🇫🇮 | 1 |

#### Statistic Summary

| **Column** | **Number Of Laps Led** |
| **Row Count** | 9 |
| **Total Sum** | 406.000 |
| **Mean μ (Average)** | 45.111 |
| **Maximum** | 151.000 |
| **75th Percentile** | 61.000 |
| **Median** | 38.000 |
| **25th Percentile** | 4.000 |
| **Minimum** | 1.000 |
| **Variance** | 1976.321 |
| **Standard Deviation σ** | 44.456 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
