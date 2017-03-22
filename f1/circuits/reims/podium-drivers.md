---
title: Rank of Formula 1® Drivers by Number of Podiums at Reims-Gueux
layout: page
collectionName: circuits
collectionId: reims
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
            "label": "Number Of Podiums"
        }
    ],
    "labels": [
        "Juan Fangio",
        "Jack Brabham",
        "Jim Clark",
        "José Froilán González",
        "Luigi Fagioli",
        "Mike Hawthorn",
        "Alberto Ascari",
        "Bruce McLaren",
        "Dan Gurney",
        "Denny Hulme",
        "Eugenio Castellotti",
        "Giancarlo Baghetti",
        "Graham Hill",
        "Jean Behra",
        "Karl Kling",
        "Luigi Villoresi",
        "Mike Parkes",
        "Olivier Gendebien",
        "Peter Collins",
        "Peter Whitehead",
        "Phil Hill",
        "Robert Manzon",
        "Stirling Moss",
        "Tony Brooks",
        "Tony Maggs",
        "Wolfgang von Trips"
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
| 1. | Juan Fangio 🇦🇷 | 4 |
| 2. | Jack Brabham 🇦🇺 | 3 |
| 3. | Jim Clark 🇬🇧 | 2 |
| 4. | José Froilán González 🇦🇷 | 2 |
| 5. | Luigi Fagioli 🇮🇹 | 2 |
| 6. | Mike Hawthorn 🇬🇧 | 2 |
| 7. | Alberto Ascari 🇮🇹 | 1 |
| 8. | Bruce McLaren 🇳🇿 | 1 |
| 9. | Dan Gurney 🇺🇸 | 1 |
| 10. | Denny Hulme 🇳🇿 | 1 |
| 11. | Eugenio Castellotti 🇮🇹 | 1 |
| 12. | Giancarlo Baghetti 🇮🇹 | 1 |
| 13. | Graham Hill 🇬🇧 | 1 |
| 14. | Jean Behra 🇫🇷 | 1 |
| 15. | Karl Kling 🇩🇪 | 1 |
| 16. | Luigi Villoresi 🇮🇹 | 1 |
| 17. | Mike Parkes 🇬🇧 | 1 |
| 18. | Olivier Gendebien 🇧🇪 | 1 |
| 19. | Peter Collins 🇬🇧 | 1 |
| 20. | Peter Whitehead 🇬🇧 | 1 |
| 21. | Phil Hill 🇺🇸 | 1 |
| 22. | Robert Manzon 🇫🇷 | 1 |
| 23. | Stirling Moss 🇬🇧 | 1 |
| 24. | Tony Brooks 🇬🇧 | 1 |
| 25. | Tony Maggs 🇿🇦 | 1 |
| 26. | Wolfgang von Trips 🇩🇪 | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 26 |
| **Total Sum** | 35.000 |
| **Mean μ (Average)** | 1.346 |
| **Maximum** | 4.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.534 |
| **Standard Deviation σ** | 0.731 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
