---
title: Rank of Formula 1® Constructor Teams by Number of DNS (Did Not Start)
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "888888",
                "888888",
                "E53524",
                "888888",
                "888888",
                "09630C",
                "243F73",
                "888888",
                "888888",
                "888888",
                "025839",
                "888888",
                "FFA500",
                "144D44",
                "888888",
                "274B72",
                "888888",
                "0F5DBB",
                "1B1D1D",
                "888888",
                "888888",
                "FA9B27",
                "273027",
                "888888",
                "C0BEC3",
                "FFFFFF",
                "888888",
                "888888",
                "AAAAAA",
                "888888",
                "888888",
                "EB212E",
                "457439",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "FFF8F6",
                "DDDDDD",
                "888888",
                "888888",
                "A3805E",
                "07316F",
                "888888",
                "1A2446",
                "888888",
                "FFFF01",
                "888888",
                "888888",
                "204FE0",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "F6CF00",
                "888888",
                "B21827",
                "888888",
                "243F73",
                "888888",
                "025839",
                "888888",
                "888888",
                "888888",
                "243F73",
                "273027",
                "888888",
                "888888",
                "BE9D56",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "2077C9",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "FFFFFF",
                "73C2FB",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "5E0A16",
                "5E0A16",
                "888888",
                "888888",
                "888888",
                "888888",
                "AAAAAA",
                "888888",
                "3da48e",
                "888888",
                "381ea0",
                "888888",
                "888888",
                "888888",
                "888888",
                "336667"
            ],
            "borderColor": [
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444"
            ],
            "borderWidth": 1,
            "data": [
                83.0,
                74.0,
                72.0,
                67.0,
                56.0,
                49.0,
                48.0,
                48.0,
                43.0,
                42.0,
                42.0,
                37.0,
                36.0,
                35.0,
                35.0,
                35.0,
                32.0,
                32.0,
                31.0,
                28.0,
                27.0,
                27.0,
                26.0,
                26.0,
                26.0,
                24.0,
                24.0,
                22.0,
                22.0,
                22.0,
                20.0,
                19.0,
                19.0,
                17.0,
                17.0,
                15.0,
                14.0,
                14.0,
                14.0,
                13.0,
                11.0,
                10.0,
                9.0,
                8.0,
                8.0,
                7.0,
                7.0,
                7.0,
                6.0,
                6.0,
                6.0,
                5.0,
                5.0,
                4.0,
                4.0,
                4.0,
                4.0,
                4.0,
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
            "label": "Did Not Start"
        }
    ],
    "labels": [
        "Osella",
        "AGS",
        "March",
        "Coloni",
        "Euro Brun",
        "Team Lotus",
        "Brabham",
        "Zakspeed",
        "ATS",
        "Ensign",
        "Lotus-Climax",
        "Toleman",
        "Arrows",
        "BRM",
        "Surtees",
        "Tyrrell",
        "Fittipaldi",
        "Ligier",
        "Minardi",
        "Rial",
        "Onyx",
        "Shadow",
        "Cooper-Climax",
        "Lambo",
        "Maserati",
        "Hesketh",
        "Pacific",
        "Footwork",
        "McLaren",
        "Merzario",
        "Lola",
        "Ferrari",
        "Lotus-BRM",
        "Fondmetal",
        "RAM",
        "Larrousse",
        "Andrea Moda",
        "Life",
        "Williams",
        "Porsche",
        "Dallara",
        "Scirocco",
        "Wolf",
        "Brabham-Ford",
        "Maki",
        "Cooper-Maserati",
        "Emeryson",
        "Jordan",
        "Leyton House",
        "McLaren-Alfa Romeo",
        "Sauber",
        "De Tomaso",
        "Iso Marlboro",
        "Bellasi",
        "Gilby",
        "HWM",
        "Renault",
        "Scarab",
        "Alfa Romeo",
        "Brabham-BRM",
        "Brabham-Repco",
        "Connaught",
        "Lotus-Ford",
        "Martini",
        "Aston Butterworth",
        "Boro",
        "Brabham-Climax",
        "Cooper",
        "Cooper-Ford",
        "Eagle-Climax",
        "HRT",
        "JBW",
        "Kauhsen",
        "LEC",
        "Lotus-Borgward",
        "March-Ford",
        "OSCA",
        "Penske",
        "Rebaque",
        "Simtek",
        "Spirit",
        "Trojan",
        "Apollon",
        "Arzani-Volpini",
        "Aston Martin",
        "BAR",
        "Benetton",
        "BRP",
        "Cisitalia",
        "Cooper-Castellotti",
        "De Tomaso-Alfa Romeo",
        "De Tomaso-Ferrari",
        "De Tomaso-Osca",
        "Embassy Hill",
        "Fry",
        "Gordini",
        "LDS-Alfa Romeo",
        "LDS-Climax",
        "Lotus-Maserati",
        "Lyncar",
        "Manor Marussia",
        "Marussia",
        "Matra",
        "MBM",
        "McGuire",
        "McLaren-BRM",
        "McLaren-Ford",
        "McLaren-Serenissima",
        "Mercedes",
        "RE",
        "Red Bull",
        "Simca",
        "Stebro",
        "Tecno",
        "Token",
        "Vanwall"
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

| # | Constructor | Did Not Start | % Of Total Participations |
|--|--|--|--|
| 1. | Osella 🇮🇹 | 83 | 32.94% |
| 2. | AGS 🇫🇷 | 74 | 60.16% |
| 3. | March 🇬🇧 | 72 | 13.74% |
| 4. | Coloni 🇮🇹 | 67 | 82.72% |
| 5. | Euro Brun 🇮🇹 | 56 | 73.68% |
| 6. | Team Lotus 🇬🇧 | 49 | 5.63% |
| 7. | Brabham 🇬🇧 | 48 | 7.25% |
| 8. | Zakspeed 🇩🇪 | 48 | 36.09% |
| 9. | ATS 🇮🇹 | 43 | 26.54% |
| 10. | Ensign 🇬🇧 | 42 | 27.27% |
| 11. | Lotus-Climax 🇬🇧 | 42 | 18.18% |
| 12. | Toleman 🇬🇧 | 37 | 28.24% |
| 13. | Arrows 🇬🇧 | 36 | 6.10% |
| 14. | BRM 🇬🇧 | 35 | 6.23% |
| 15. | Surtees 🇬🇧 | 35 | 13.46% |
| 16. | Tyrrell 🇬🇧 | 35 | 3.97% |
| 17. | Fittipaldi 🇧🇷 | 32 | 20.65% |
| 18. | Ligier 🇫🇷 | 32 | 5.24% |
| 19. | Minardi 🇮🇹 | 31 | 4.61% |
| 20. | Rial 🇩🇪 | 28 | 58.33% |
| 21. | Onyx 🇬🇧 | 27 | 51.92% |
| 22. | Shadow 🇬🇧 | 27 | 12.80% |
| 23. | Cooper-Climax 🇬🇧 | 26 | 9.70% |
| 24. | Lambo 🇮🇹 | 26 | 81.25% |
| 25. | Maserati 🇮🇹 | 26 | 5.96% |
| 26. | Hesketh 🇬🇧 | 24 | 24.74% |
| 27. | Pacific 🇬🇧 | 24 | 36.36% |
| 28. | Footwork 🇬🇧 | 22 | 11.34% |
| 29. | McLaren 🇬🇧 | 22 | 1.39% |
| 30. | Merzario 🇮🇹 | 22 | 68.75% |
| 31. | Lola 🇬🇧 | 20 | 12.12% |
| 32. | Ferrari 🇮🇹 | 19 | 0.90% |
| 33. | Lotus-BRM 🇬🇧 | 19 | 15.70% |
| 34. | Fondmetal 🇮🇹 | 17 | 40.48% |
| 35. | RAM 🇬🇧 | 17 | 23.94% |
| 36. | Larrousse 🇫🇷 | 15 | 6.94% |
| 37. | Andrea Moda 🇮🇹 | 14 | 93.33% |
| 38. | Life 🇮🇹 | 14 | 100.00% |
| 39. | Williams 🇬🇧 | 14 | 1.05% |
| 40. | Porsche 🇩🇪 | 13 | 15.48% |
| 41. | Dallara 🇮🇹 | 11 | 7.64% |
| 42. | Scirocco 🇬🇧 | 10 | 58.82% |
| 43. | Wolf 🇨🇦 | 9 | 11.39% |
| 44. | Brabham-Ford 🇬🇧 | 8 | 13.79% |
| 45. | Maki 🇯🇵 | 8 | 100.00% |
| 46. | Cooper-Maserati 🇬🇧 | 7 | 5.22% |
| 47. | Emeryson 🇬🇧 | 7 | 63.64% |
| 48. | Jordan 🇮🇪 | 7 | 1.40% |
| 49. | Leyton House 🇬🇧 | 6 | 9.38% |
| 50. | McLaren-Alfa Romeo 🇬🇧 | 6 | 54.55% |
| 51. | Sauber 🇨🇭 | 6 | 0.85% |
| 52. | De Tomaso 🇮🇹 | 5 | 35.71% |
| 53. | Iso Marlboro 🇬🇧 | 5 | 9.09% |
| 54. | Bellasi 🇨🇭 | 4 | 66.67% |
| 55. | Gilby 🇬🇧 | 4 | 57.14% |
| 56. | HWM 🇬🇧 | 4 | 8.51% |
| 57. | Renault 🇫🇷 | 4 | 0.64% |
| 58. | Scarab 🇺🇸 | 4 | 44.44% |
| 59. | Alfa Romeo 🇮🇹 | 3 | 1.23% |
| 60. | Brabham-BRM 🇬🇧 | 3 | 7.32% |
| 61. | Brabham-Repco 🇬🇧 | 3 | 3.90% |
| 62. | Connaught 🇬🇧 | 3 | 5.56% |
| 63. | Lotus-Ford 🇬🇧 | 3 | 2.34% |
| 64. | Martini 🇫🇷 | 3 | 37.50% |
| 65. | Aston Butterworth 🇬🇧 | 2 | 50.00% |
| 66. | Boro 🇳🇱 | 2 | 25.00% |
| 67. | Brabham-Climax 🇬🇧 | 2 | 2.15% |
| 68. | Cooper 🇬🇧 | 2 | 1.94% |
| 69. | Cooper-Ford 🇬🇧 | 2 | 100.00% |
| 70. | Eagle-Climax 🇺🇸 | 2 | 15.38% |
| 71. | HRT 🇪🇸 | 2 | 1.75% |
| 72. | JBW 🇬🇧 | 2 | 33.33% |
| 73. | Kauhsen 🇩🇪 | 2 | 100.00% |
| 74. | LEC 🇬🇧 | 2 | 40.00% |
| 75. | Lotus-Borgward 🇬🇧 | 2 | 100.00% |
| 76. | March-Ford 🇬🇧 | 2 | 4.65% |
| 77. | OSCA 🇮🇹 | 2 | 25.00% |
| 78. | Penske 🇺🇸 | 2 | 4.35% |
| 79. | Rebaque 🇲🇽 | 2 | 66.67% |
| 80. | Simtek 🇬🇧 | 2 | 5.00% |
| 81. | Spirit 🇬🇧 | 2 | 8.00% |
| 82. | Trojan 🇬🇧 | 2 | 25.00% |
| 83. | Apollon 🇨🇭 | 1 | 100.00% |
| 84. | Arzani-Volpini 🇮🇹 | 1 | 100.00% |
| 85. | Aston Martin 🇬🇧 | 1 | 9.09% |
| 86. | BAR 🇬🇧 | 1 | 0.42% |
| 87. | Benetton 🇮🇹 | 1 | 0.19% |
| 88. | BRP 🇬🇧 | 1 | 5.26% |
| 89. | Cisitalia 🇮🇹 | 1 | 100.00% |
| 90. | Cooper-Castellotti 🇬🇧 | 1 | 16.67% |
| 91. | De Tomaso-Alfa Romeo 🇮🇹 | 1 | 33.33% |
| 92. | De Tomaso-Ferrari 🇮🇹 | 1 | 100.00% |
| 93. | De Tomaso-Osca 🇮🇹 | 1 | 33.33% |
| 94. | Embassy Hill 🇬🇧 | 1 | 5.26% |
| 95. | Fry 🇬🇧 | 1 | 100.00% |
| 96. | Gordini 🇫🇷 | 1 | 0.98% |
| 97. | LDS-Alfa Romeo 🇿🇦 | 1 | 50.00% |
| 98. | LDS-Climax 🇿🇦 | 1 | 50.00% |
| 99. | Lotus-Maserati 🇬🇧 | 1 | 50.00% |
| 100. | Lyncar 🇬🇧 | 1 | 50.00% |
| 101. | Manor Marussia 🇬🇧 | 1 | 1.28% |
| 102. | Marussia 🇷🇺 | 1 | 0.92% |
| 103. | Matra 🇫🇷 | 1 | 1.41% |
| 104. | MBM 🇨🇭 | 1 | 100.00% |
| 105. | McGuire 🇦🇺 | 1 | 100.00% |
| 106. | McLaren-BRM 🇬🇧 | 1 | 7.14% |
| 107. | McLaren-Ford 🇬🇧 | 1 | 1.15% |
| 108. | McLaren-Serenissima 🇬🇧 | 1 | 50.00% |
| 109. | Mercedes 🇩🇪 | 1 | 0.32% |
| 110. | RE 🇿🇼 | 1 | 100.00% |
| 111. | Red Bull 🇦🇹 | 1 | 0.22% |
| 112. | Simca 🇫🇷 | 1 | 3.45% |
| 113. | Stebro 🇨🇦 | 1 | 50.00% |
| 114. | Tecno 🇮🇹 | 1 | 9.09% |
| 115. | Token 🇬🇧 | 1 | 25.00% |
| 116. | Vanwall 🇬🇧 | 1 | 1.41% |

#### Statistic Summary

| **Row Count** | 116.000 |
| **Total Sum** | 1536.000 |
| **Mean (Average)** | 13.241 |
| **Maximum** | 83.000 |
| **75th Percentile** | 22.000 |
| **Median** | 4.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 319.838 |
| **Standard Deviation** | 17.884 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
