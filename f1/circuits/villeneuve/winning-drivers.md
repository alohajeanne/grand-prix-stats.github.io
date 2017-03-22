---
title: Rank of Formula 1® Drivers by Number of Wins at Circuit Gilles Villeneuve
layout: page
collectionName: circuits
collectionId: villeneuve
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
                7.0,
                5.0,
                3.0,
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
                1.0,
                1.0
            ],
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Lewis Hamilton",
        "Nelson Piquet",
        "Alan Jones",
        "Ayrton Senna",
        "Alain Prost",
        "Damon Hill",
        "Daniel Ricciardo",
        "Fernando Alonso",
        "Gerhard Berger",
        "Gilles Villeneuve",
        "Jacques Laffite",
        "Jean Alesi",
        "Jenson Button",
        "Kimi Räikkönen",
        "Michele Alboreto",
        "Mika Häkkinen",
        "Nigel Mansell",
        "Ralf Schumacher",
        "René Arnoux",
        "Robert Kubica",
        "Sebastian Vettel",
        "Thierry Boutsen"
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
| 1. | Michael Schumacher 🇩🇪 | 7 |
| 2. | Lewis Hamilton 🇬🇧 | 5 |
| 3. | Nelson Piquet 🇧🇷 | 3 |
| 4. | Alan Jones 🇦🇺 | 2 |
| 5. | Ayrton Senna 🇧🇷 | 2 |
| 6. | Alain Prost 🇫🇷 | 1 |
| 7. | Damon Hill 🇬🇧 | 1 |
| 8. | Daniel Ricciardo 🇦🇺 | 1 |
| 9. | Fernando Alonso 🇪🇸 | 1 |
| 10. | Gerhard Berger 🇦🇹 | 1 |
| 11. | Gilles Villeneuve 🇨🇦 | 1 |
| 12. | Jacques Laffite 🇫🇷 | 1 |
| 13. | Jean Alesi 🇫🇷 | 1 |
| 14. | Jenson Button 🇬🇧 | 1 |
| 15. | Kimi Räikkönen 🇫🇮 | 1 |
| 16. | Michele Alboreto 🇮🇹 | 1 |
| 17. | Mika Häkkinen 🇫🇮 | 1 |
| 18. | Nigel Mansell 🇬🇧 | 1 |
| 19. | Ralf Schumacher 🇩🇪 | 1 |
| 20. | René Arnoux 🇫🇷 | 1 |
| 21. | Robert Kubica 🇵🇱 | 1 |
| 22. | Sebastian Vettel 🇩🇪 | 1 |
| 23. | Thierry Boutsen 🇧🇪 | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 23 |
| **Total Sum** | 37.000 |
| **Mean μ (Average)** | 1.609 |
| **Maximum** | 7.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 2.151 |
| **Standard Deviation σ** | 1.467 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
