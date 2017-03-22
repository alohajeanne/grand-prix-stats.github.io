---
title: List of All Formula 1® Drivers that Have Been in the Podium in Sweden by Number of Times
layout: page
collectionName: countries
collectionId: sweden
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
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
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
                1.0
            ],
            "label": "Times"
        }
    ],
    "labels": [
        "Niki Lauda",
        "Carlos Reutemann",
        "Jody Scheckter",
        "Patrick Depailler",
        "Ronnie Peterson",
        "Clay Regazzoni",
        "Denny Hulme",
        "François Cevert",
        "Jacques Laffite",
        "James Hunt",
        "Jochen Mass",
        "Riccardo Patrese"
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
| 1. | Niki Lauda 🇦🇹 | 3 |
| 2. | Carlos Reutemann 🇦🇷 | 2 |
| 3. | Jody Scheckter 🇿🇦 | 2 |
| 4. | Patrick Depailler 🇫🇷 | 2 |
| 5. | Ronnie Peterson 🇸🇪 | 2 |
| 6. | Clay Regazzoni 🇨🇭 | 1 |
| 7. | Denny Hulme 🇳🇿 | 1 |
| 8. | François Cevert 🇫🇷 | 1 |
| 9. | Jacques Laffite 🇫🇷 | 1 |
| 10. | James Hunt 🇬🇧 | 1 |
| 11. | Jochen Mass 🇩🇪 | 1 |
| 12. | Riccardo Patrese 🇮🇹 | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 12 |
| **Total Sum** | 18.000 |
| **Mean μ (Average)** | 1.500 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.417 |
| **Standard Deviation σ** | 0.645 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
