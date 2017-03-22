---
title: Rank of Formula 1® Drivers by Number of Podiums at Albert Park Grand Prix Circuit
layout: page
collectionName: circuits
collectionId: albert_park
---

{% assign url_split = page.url | split: "/" %}
<div id="collection-navigation">
<button onclick="selector.options[selector.selectedIndex-1].value && (window.location = selector.options[selector.selectedIndex-1].value);">&lt; Prev</button>
<button onclick="selector.options[selector.selectedIndex+1].value && (window.location = selector.options[selector.selectedIndex+1].value);">Next &gt;</button>
<select id="selector" onchange="this.options[this.selectedIndex].value && (window.location = this.options[this.selectedIndex].value);">
  {% for collectionId in site.data[page.collectionName].refs %}
    {% if collectionId == page.collectionId %}
      {% assign selected = "selected" %}
    {% else %}
      {% assign selected = "" %}
    {% endif %}
    {% assign profile = site.data[page.collectionName][collectionId].profile %}
    <option value="/f1/{{ page.collectionName }}/{{ collectionId }}/{{ url_split[4] }}" {{ selected }}>{{ profile.collection_name }}</option>
  {% endfor %}
</select>
</div>

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
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                6.0,
                5.0,
                5.0,
                5.0,
                5.0,
                5.0,
                4.0,
                4.0,
                4.0,
                3.0,
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
                1.0
            ],
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Lewis Hamilton",
        "Fernando Alonso",
        "Kimi Räikkönen",
        "Michael Schumacher",
        "Rubens Barrichello",
        "Sebastian Vettel",
        "David Coulthard",
        "Jenson Button",
        "Nico Rosberg",
        "Ralf Schumacher",
        "Eddie Irvine",
        "Heinz-Harald Frentzen",
        "Juan Pablo Montoya",
        "Mika Häkkinen",
        "Damon Hill",
        "Felipe Massa",
        "Giancarlo Fisichella",
        "Jacques Villeneuve",
        "Jarno Trulli",
        "Kevin Magnussen",
        "Nick Heidfeld",
        "Robert Kubica",
        "Vitaly Petrov"
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
| 1. | Lewis Hamilton 🇬🇧 | 6 |
| 2. | Fernando Alonso 🇪🇸 | 5 |
| 3. | Kimi Räikkönen 🇫🇮 | 5 |
| 4. | Michael Schumacher 🇩🇪 | 5 |
| 5. | Rubens Barrichello 🇧🇷 | 5 |
| 6. | Sebastian Vettel 🇩🇪 | 5 |
| 7. | David Coulthard 🇬🇧 | 4 |
| 8. | Jenson Button 🇬🇧 | 4 |
| 9. | Nico Rosberg 🇩🇪 | 4 |
| 10. | Ralf Schumacher 🇩🇪 | 3 |
| 11. | Eddie Irvine 🇬🇧 | 2 |
| 12. | Heinz-Harald Frentzen 🇩🇪 | 2 |
| 13. | Juan Pablo Montoya 🇨🇴 | 2 |
| 14. | Mika Häkkinen 🇫🇮 | 2 |
| 15. | Damon Hill 🇬🇧 | 1 |
| 16. | Felipe Massa 🇧🇷 | 1 |
| 17. | Giancarlo Fisichella 🇮🇹 | 1 |
| 18. | Jacques Villeneuve 🇨🇦 | 1 |
| 19. | Jarno Trulli 🇮🇹 | 1 |
| 20. | Kevin Magnussen 🇩🇰 | 1 |
| 21. | Nick Heidfeld 🇩🇪 | 1 |
| 22. | Robert Kubica 🇵🇱 | 1 |
| 23. | Vitaly Petrov 🇷🇺 | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 23 |
| **Total Sum** | 63.000 |
| **Mean μ (Average)** | 2.739 |
| **Maximum** | 6.000 |
| **75th Percentile** | 5.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 3.062 |
| **Standard Deviation σ** | 1.750 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
