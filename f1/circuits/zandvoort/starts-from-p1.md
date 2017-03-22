---
title: Rank of Formula 1® Drivers by Number of Starts from P1 at Circuit Park Zandvoort
layout: page
collectionName: circuits
collectionId: zandvoort
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
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
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
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Starts From P1"
        }
    ],
    "labels": [
        "René Arnoux",
        "Alain Prost",
        "Alberto Ascari",
        "Graham Hill",
        "Jochen Rindt",
        "Mario Andretti",
        "Nelson Piquet",
        "Niki Lauda",
        "Ronnie Peterson",
        "Chris Amon",
        "Dan Gurney",
        "Jack Brabham",
        "Jacky Ickx",
        "Jim Clark",
        "Jo Bonnier",
        "John Surtees",
        "Juan Fangio",
        "Phil Hill",
        "Stirling Moss",
        "Stuart Lewis-Evans"
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
| 1. | René Arnoux 🇫🇷 | 3 |
| 2. | Alain Prost 🇫🇷 | 2 |
| 3. | Alberto Ascari 🇮🇹 | 2 |
| 4. | Graham Hill 🇬🇧 | 2 |
| 5. | Jochen Rindt 🇦🇹 | 2 |
| 6. | Mario Andretti 🇺🇸 | 2 |
| 7. | Nelson Piquet 🇧🇷 | 2 |
| 8. | Niki Lauda 🇦🇹 | 2 |
| 9. | Ronnie Peterson 🇸🇪 | 2 |
| 10. | Chris Amon 🇳🇿 | 1 |
| 11. | Dan Gurney 🇺🇸 | 1 |
| 12. | Jack Brabham 🇦🇺 | 1 |
| 13. | Jacky Ickx 🇧🇪 | 1 |
| 14. | Jim Clark 🇬🇧 | 1 |
| 15. | Jo Bonnier 🇸🇪 | 1 |
| 16. | John Surtees 🇬🇧 | 1 |
| 17. | Juan Fangio 🇦🇷 | 1 |
| 18. | Phil Hill 🇺🇸 | 1 |
| 19. | Stirling Moss 🇬🇧 | 1 |
| 20. | Stuart Lewis-Evans 🇬🇧 | 1 |

#### Statistic Summary

| **Column** | **Number Of Starts From P1** |
| **Row Count** | 20 |
| **Total Sum** | 30.000 |
| **Mean μ (Average)** | 1.500 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.350 |
| **Standard Deviation σ** | 0.592 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
