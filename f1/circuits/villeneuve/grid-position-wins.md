---
title: Rank of Grid Position by Number of Wins at Circuit Gilles Villeneuve
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
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                17.0,
                6.0,
                4.0,
                3.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0
            ],
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "1",
        "2",
        "3",
        "6",
        "4",
        "7",
        "5",
        "8",
        "10",
        "9",
        "11",
        "12",
        "13",
        "14",
        "15",
        "16",
        "17",
        "18",
        "19",
        "20",
        "21",
        "22",
        "23",
        "24",
        "25",
        "26"
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

| # | Grid Position | Number Of Wins |
|--|--|--|
| 1. | 1 | 17 |
| 2. | 2 | 6 |
| 3. | 3 | 4 |
| 4. | 6 | 3 |
| 5. | 4 | 2 |
| 6. | 7 | 2 |
| 7. | 5 | 1 |
| 8. | 8 | 1 |
| 9. | 10 | 1 |
| 10. | 9 | 0 |
| 11. | 11 | 0 |
| 12. | 12 | 0 |
| 13. | 13 | 0 |
| 14. | 14 | 0 |
| 15. | 15 | 0 |
| 16. | 16 | 0 |
| 17. | 17 | 0 |
| 18. | 18 | 0 |
| 19. | 19 | 0 |
| 20. | 20 | 0 |
| 21. | 21 | 0 |
| 22. | 22 | 0 |
| 23. | 23 | 0 |
| 24. | 24 | 0 |
| 25. | 25 | 0 |
| 26. | 26 | 0 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 26 |
| **Total Sum** | 37.000 |
| **Mean μ (Average)** | 1.423 |
| **Maximum** | 17.000 |
| **75th Percentile** | 1.000 |
| **Median** |  |
| **25th Percentile** |  |
| **Minimum** |  |
| **Variance** | 11.859 |
| **Standard Deviation σ** | 3.444 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})