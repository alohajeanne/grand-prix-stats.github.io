---
title: Number of Winning Drivers per Formula 1® Season
layout: page
---



<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.5.0/Chart.bundle.js"></script>

<canvas id="chart" width="400" height="800"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": "#f3a935",
            "borderColor": "#f68639",
            "borderWidth": 1,
            "data": [
                3,
                6,
                3,
                5,
                4,
                4,
                5,
                4,
                6,
                6,
                5,
                5,
                4,
                3,
                5,
                4,
                5,
                6,
                7,
                5,
                7,
                6,
                5,
                5,
                7,
                9,
                7,
                8,
                6,
                7,
                7,
                7,
                11,
                8,
                5,
                8,
                5,
                5,
                3,
                6,
                6,
                5,
                5,
                4,
                4,
                5,
                4,
                6,
                4,
                6,
                4,
                5,
                4,
                8,
                5,
                5,
                5,
                4,
                7,
                6,
                5,
                5,
                8,
                5,
                3,
                3,
                4,
                0
            ],
            "label": "Count"
        }
    ],
    "labels": [
        "1950",
        "1951",
        "1952",
        "1953",
        "1954",
        "1955",
        "1956",
        "1957",
        "1958",
        "1959",
        "1960",
        "1961",
        "1962",
        "1963",
        "1964",
        "1965",
        "1966",
        "1967",
        "1968",
        "1969",
        "1970",
        "1971",
        "1972",
        "1973",
        "1974",
        "1975",
        "1976",
        "1977",
        "1978",
        "1979",
        "1980",
        "1981",
        "1982",
        "1983",
        "1984",
        "1985",
        "1986",
        "1987",
        "1988",
        "1989",
        "1990",
        "1991",
        "1992",
        "1993",
        "1994",
        "1995",
        "1996",
        "1997",
        "1998",
        "1999",
        "2000",
        "2001",
        "2002",
        "2003",
        "2004",
        "2005",
        "2006",
        "2007",
        "2008",
        "2009",
        "2010",
        "2011",
        "2012",
        "2013",
        "2014",
        "2015",
        "2016",
        "2017"
    ]
};

var options = {
  legend: {
    display: false
  },
  scales: {
    xAxes: [{
      ticks: {
        beginAtZero: true
      }
    }],
    yAxes: [{
      ticks: {
        beginAtZero: true
      }
    }]
  }
};
new Chart("chart", {
    data: data,
    type: 'horizontalBar',
    options: options
});
</script>

#### Data Table

| Year | Count |
|--|--|
| 1950 | 3 |
| 1951 | 6 |
| 1952 | 3 |
| 1953 | 5 |
| 1954 | 4 |
| 1955 | 4 |
| 1956 | 5 |
| 1957 | 4 |
| 1958 | 6 |
| 1959 | 6 |
| 1960 | 5 |
| 1961 | 5 |
| 1962 | 4 |
| 1963 | 3 |
| 1964 | 5 |
| 1965 | 4 |
| 1966 | 5 |
| 1967 | 6 |
| 1968 | 7 |
| 1969 | 5 |
| 1970 | 7 |
| 1971 | 6 |
| 1972 | 5 |
| 1973 | 5 |
| 1974 | 7 |
| 1975 | 9 |
| 1976 | 7 |
| 1977 | 8 |
| 1978 | 6 |
| 1979 | 7 |
| 1980 | 7 |
| 1981 | 7 |
| 1982 | 11 |
| 1983 | 8 |
| 1984 | 5 |
| 1985 | 8 |
| 1986 | 5 |
| 1987 | 5 |
| 1988 | 3 |
| 1989 | 6 |
| 1990 | 6 |
| 1991 | 5 |
| 1992 | 5 |
| 1993 | 4 |
| 1994 | 4 |
| 1995 | 5 |
| 1996 | 4 |
| 1997 | 6 |
| 1998 | 4 |
| 1999 | 6 |
| 2000 | 4 |
| 2001 | 5 |
| 2002 | 4 |
| 2003 | 8 |
| 2004 | 5 |
| 2005 | 5 |
| 2006 | 5 |
| 2007 | 4 |
| 2008 | 7 |
| 2009 | 6 |
| 2010 | 5 |
| 2011 | 5 |
| 2012 | 8 |
| 2013 | 5 |
| 2014 | 3 |
| 2015 | 3 |
| 2016 | 4 |
| 2017 | 0 |