---
title: Rank of Formula 1® Drivers by Number of Podiums at Autódromo Hermanos Rodríguez
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
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                4.0,
                4.0,
                4.0,
                4.0,
                4.0,
                3.0,
                3.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Ayrton Senna",
        "Denny Hulme",
        "Jack Brabham",
        "Nigel Mansell",
        "Riccardo Patrese",
        "Alain Prost",
        "Gerhard Berger",
        "Dan Gurney",
        "Jacky Ickx",
        "Jim Clark",
        "John Surtees",
        "Lewis Hamilton",
        "Nico Rosberg",
        "Richie Ginther",
        "Bruce McLaren",
        "Clay Regazzoni",
        "Daniel Ricciardo",
        "Graham Hill",
        "Jackie Oliver",
        "Lorenzo Bandini",
        "Michael Schumacher",
        "Michele Alboreto",
        "Mike Spence",
        "Nelson Piquet",
        "Valtteri Bottas"
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

| # | Driver | Number Of Podiums |
|--|--|--|
| 1. | Ayrton Senna 🇧🇷 | 4 |
| 2. | Denny Hulme 🇳🇿 | 4 |
| 3. | Jack Brabham 🇦🇺 | 4 |
| 4. | Nigel Mansell 🇬🇧 | 4 |
| 5. | Riccardo Patrese 🇮🇹 | 4 |
| 6. | Alain Prost 🇫🇷 | 3 |
| 7. | Gerhard Berger 🇦🇹 | 3 |
| 8. | Dan Gurney 🇺🇸 | 2 |
| 9. | Jacky Ickx 🇧🇪 | 2 |
| 10. | Jim Clark 🇬🇧 | 2 |
| 11. | John Surtees 🇬🇧 | 2 |
| 12. | Lewis Hamilton 🇬🇧 | 2 |
| 13. | Nico Rosberg 🇩🇪 | 2 |
| 14. | Richie Ginther 🇺🇸 | 2 |
| 15. | Bruce McLaren 🇳🇿 | 1 |
| 16. | Clay Regazzoni 🇨🇭 | 1 |
| 17. | Daniel Ricciardo 🇦🇺 | 1 |
| 18. | Graham Hill 🇬🇧 | 1 |
| 19. | Jackie Oliver 🇬🇧 | 1 |
| 20. | Lorenzo Bandini 🇮🇹 | 1 |
| 21. | Michael Schumacher 🇩🇪 | 1 |
| 22. | Michele Alboreto 🇮🇹 | 1 |
| 23. | Mike Spence 🇬🇧 | 1 |
| 24. | Nelson Piquet 🇧🇷 | 1 |
| 25. | Valtteri Bottas 🇫🇮 | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 25 |
| **Total Sum** | 51.000 |
| **Mean μ (Average)** | 2.040 |
| **Maximum** | 4.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.318 |
| **Standard Deviation σ** | 1.148 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
