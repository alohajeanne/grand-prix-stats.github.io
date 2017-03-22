---
title: List of All Formula 1® Drivers that Have Won a Race in Australia by Number of Times
layout: page
collectionName: countries
collectionId: australia
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
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                4.0,
                3.0,
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
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Jenson Button",
        "Alain Prost",
        "Ayrton Senna",
        "Damon Hill",
        "David Coulthard",
        "Gerhard Berger",
        "Kimi Räikkönen",
        "Lewis Hamilton",
        "Nico Rosberg",
        "Eddie Irvine",
        "Fernando Alonso",
        "Giancarlo Fisichella",
        "Keke Rosberg",
        "Mika Häkkinen",
        "Nelson Piquet",
        "Nigel Mansell",
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

| # | Driver | Times |
|--|--|--|
| 1. | Michael Schumacher 🇩🇪 | 4 |
| 2. | Jenson Button 🇬🇧 | 3 |
| 3. | Alain Prost 🇫🇷 | 2 |
| 4. | Ayrton Senna 🇧🇷 | 2 |
| 5. | Damon Hill 🇬🇧 | 2 |
| 6. | David Coulthard 🇬🇧 | 2 |
| 7. | Gerhard Berger 🇦🇹 | 2 |
| 8. | Kimi Räikkönen 🇫🇮 | 2 |
| 9. | Lewis Hamilton 🇬🇧 | 2 |
| 10. | Nico Rosberg 🇩🇪 | 2 |
| 11. | Eddie Irvine 🇬🇧 | 1 |
| 12. | Fernando Alonso 🇪🇸 | 1 |
| 13. | Giancarlo Fisichella 🇮🇹 | 1 |
| 14. | Keke Rosberg 🇫🇮 | 1 |
| 15. | Mika Häkkinen 🇫🇮 | 1 |
| 16. | Nelson Piquet 🇧🇷 | 1 |
| 17. | Nigel Mansell 🇬🇧 | 1 |
| 18. | Sebastian Vettel 🇩🇪 | 1 |
| 19. | Thierry Boutsen 🇧🇪 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 19 |
| **Total Sum** | 32.000 |
| **Mean μ (Average)** | 1.684 |
| **Maximum** | 4.000 |
| **75th Percentile** | 2.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.637 |
| **Standard Deviation σ** | 0.798 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
