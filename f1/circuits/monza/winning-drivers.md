---
title: Rank of Formula 1® Drivers by Number of Wins at Autodromo Nazionale di Monza
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
                5.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                2.0,
                2.0,
                2.0,
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
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Alain Prost",
        "Juan Fangio",
        "Lewis Hamilton",
        "Nelson Piquet",
        "Ronnie Peterson",
        "Rubens Barrichello",
        "Sebastian Vettel",
        "Stirling Moss",
        "Alberto Ascari",
        "Ayrton Senna",
        "Clay Regazzoni",
        "Damon Hill",
        "Fernando Alonso",
        "Jackie Stewart",
        "John Surtees",
        "Juan Pablo Montoya",
        "Niki Lauda",
        "Phil Hill",
        "David Coulthard",
        "Denny Hulme",
        "Emerson Fittipaldi",
        "Gerhard Berger",
        "Graham Hill",
        "Heinz-Harald Frentzen",
        "Jim Clark",
        "Jody Scheckter",
        "Johnny Herbert",
        "Ludovico Scarfiotti",
        "Mario Andretti",
        "Nico Rosberg",
        "Nigel Mansell",
        "Nino Farina",
        "Peter Gethin",
        "René Arnoux",
        "Tony Brooks"
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

| # | Driver | Number Of Wins |
|--|--|--|
| 1. | Michael Schumacher 🇩🇪 | 5 |
| 2. | Alain Prost 🇫🇷 | 3 |
| 3. | Juan Fangio 🇦🇷 | 3 |
| 4. | Lewis Hamilton 🇬🇧 | 3 |
| 5. | Nelson Piquet 🇧🇷 | 3 |
| 6. | Ronnie Peterson 🇸🇪 | 3 |
| 7. | Rubens Barrichello 🇧🇷 | 3 |
| 8. | Sebastian Vettel 🇩🇪 | 3 |
| 9. | Stirling Moss 🇬🇧 | 3 |
| 10. | Alberto Ascari 🇮🇹 | 2 |
| 11. | Ayrton Senna 🇧🇷 | 2 |
| 12. | Clay Regazzoni 🇨🇭 | 2 |
| 13. | Damon Hill 🇬🇧 | 2 |
| 14. | Fernando Alonso 🇪🇸 | 2 |
| 15. | Jackie Stewart 🇬🇧 | 2 |
| 16. | John Surtees 🇬🇧 | 2 |
| 17. | Juan Pablo Montoya 🇨🇴 | 2 |
| 18. | Niki Lauda 🇦🇹 | 2 |
| 19. | Phil Hill 🇺🇸 | 2 |
| 20. | David Coulthard 🇬🇧 | 1 |
| 21. | Denny Hulme 🇳🇿 | 1 |
| 22. | Emerson Fittipaldi 🇧🇷 | 1 |
| 23. | Gerhard Berger 🇦🇹 | 1 |
| 24. | Graham Hill 🇬🇧 | 1 |
| 25. | Heinz-Harald Frentzen 🇩🇪 | 1 |
| 26. | Jim Clark 🇬🇧 | 1 |
| 27. | Jody Scheckter 🇿🇦 | 1 |
| 28. | Johnny Herbert 🇬🇧 | 1 |
| 29. | Ludovico Scarfiotti 🇮🇹 | 1 |
| 30. | Mario Andretti 🇺🇸 | 1 |
| 31. | Nico Rosberg 🇩🇪 | 1 |
| 32. | Nigel Mansell 🇬🇧 | 1 |
| 33. | Nino Farina 🇮🇹 | 1 |
| 34. | Peter Gethin 🇬🇧 | 1 |
| 35. | René Arnoux 🇫🇷 | 1 |
| 36. | Tony Brooks 🇬🇧 | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 36 |
| **Total Sum** | 66.000 |
| **Mean μ (Average)** | 1.833 |
| **Maximum** | 5.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.917 |
| **Standard Deviation σ** | 0.957 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
