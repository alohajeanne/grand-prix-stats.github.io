---
title: Rank of Formula 1® Drivers by Number of Laps Led at Sepang International Circuit
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
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
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
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
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
                175.0,
                169.0,
                147.0,
                114.0,
                75.0,
                43.0,
                39.0,
                34.0,
                33.0,
                31.0,
                27.0,
                18.0,
                17.0,
                16.0,
                16.0,
                8.0,
                6.0,
                4.0,
                4.0,
                3.0,
                2.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Sebastian Vettel",
        "Fernando Alonso",
        "Michael Schumacher",
        "Lewis Hamilton",
        "Kimi Räikkönen",
        "Giancarlo Fisichella",
        "Eddie Irvine",
        "Mark Webber",
        "Rubens Barrichello",
        "Ralf Schumacher",
        "David Coulthard",
        "Jenson Button",
        "Daniel Ricciardo",
        "Felipe Massa",
        "Nico Rosberg",
        "Robert Kubica",
        "Max Verstappen",
        "Jarno Trulli",
        "Sergio Pérez",
        "Juan Pablo Montoya",
        "Mika Häkkinen",
        "Nick Heidfeld"
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
| 1. | Sebastian Vettel 🇩🇪 | 175 |
| 2. | Fernando Alonso 🇪🇸 | 169 |
| 3. | Michael Schumacher 🇩🇪 | 147 |
| 4. | Lewis Hamilton 🇬🇧 | 114 |
| 5. | Kimi Räikkönen 🇫🇮 | 75 |
| 6. | Giancarlo Fisichella 🇮🇹 | 43 |
| 7. | Eddie Irvine 🇬🇧 | 39 |
| 8. | Mark Webber 🇦🇺 | 34 |
| 9. | Rubens Barrichello 🇧🇷 | 33 |
| 10. | Ralf Schumacher 🇩🇪 | 31 |
| 11. | David Coulthard 🇬🇧 | 27 |
| 12. | Jenson Button 🇬🇧 | 18 |
| 13. | Daniel Ricciardo 🇦🇺 | 17 |
| 14. | Felipe Massa 🇧🇷 | 16 |
| 15. | Nico Rosberg 🇩🇪 | 16 |
| 16. | Robert Kubica 🇵🇱 | 8 |
| 17. | Max Verstappen 🇳🇱 | 6 |
| 18. | Jarno Trulli 🇮🇹 | 4 |
| 19. | Sergio Pérez 🇲🇽 | 4 |
| 20. | Juan Pablo Montoya 🇨🇴 | 3 |
| 21. | Mika Häkkinen 🇫🇮 | 2 |
| 22. | Nick Heidfeld 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Number Of Laps Led** |
| **Row Count** | 22 |
| **Total Sum** | 982.000 |
| **Mean μ (Average)** | 44.636 |
| **Maximum** | 175.000 |
| **75th Percentile** | 43.000 |
| **Median** | 27.000 |
| **25th Percentile** | 6.000 |
| **Minimum** | 1.000 |
| **Variance** | 2916.322 |
| **Standard Deviation σ** | 54.003 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
