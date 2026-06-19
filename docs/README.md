# Insights

## Overview

```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "height": 300,
  "title": "Top 10 Repositories by Visitors",
  "data": {
    "values": [
      {"repository": "NonGKI_Kernel_Build_2nd", "views": 393}, {"repository": "n0_kernel_pipa", "views": 272}
    ]
  },
  "mark": {
    "type": "bar",
    "color": "#ff7f0e"
  },
  "encoding": {
    "y": {"field": "repository", "type": "nominal", "title": "Repository", "sort": "-x"},
    "x": {"field": "views", "type": "quantitative", "title": "Total Views"}
  }
}
```


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "height": 300,
  "title": "Top 10 Repositories by Git Clones",
  "data": {
    "values": [
      {"repository": "NonGKI_Kernel_Build_2nd", "clones": 416}, {"repository": "n0_kernel_pipa", "clones": 354}
    ]
  },
  "mark": {
    "type": "bar",
    "color": "#ff7f0e"
  },
  "encoding": {
    "y": {"field": "repository", "type": "nominal", "title": "Repository", "sort": "-x"},
    "x": {"field": "clones", "type": "quantitative", "title": "Total Clones"}
  }
}
```

## Repository Breakdown

### bcggxx/n0_kernel_pipa

[![GitHub Repo](https://img.shields.io/badge/-Repository-white?logo=github&logoColor=181717&style=social)](https://github.com/bcggxx/n0_kernel_pipa)&nbsp;
[![GitHub Stars](https://img.shields.io/github/stars/bcggxx/n0_kernel_pipa?style=social)](https://github.com/bcggxx/n0_kernel_pipa/stargazers)&nbsp;
[![GitHub Forks](https://img.shields.io/github/forks/bcggxx/n0_kernel_pipa?style=social)](https://github.com/bcggxx/n0_kernel_pipa/network/members)&nbsp;
[![GitHub Watchers](https://img.shields.io/github/watchers/bcggxx/n0_kernel_pipa?style=social)](https://github.com/bcggxx/n0_kernel_pipa/watchers)


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Visitors for bcggxx/n0_kernel_pipa",
  "data": {
    "values": [
      {"date": "2026-05-31", "type": "Total Views", "value": 0},
      {"date": "2026-06-01", "type": "Total Views", "value": 1},
      {"date": "2026-06-02", "type": "Total Views", "value": 0},
      {"date": "2026-06-03", "type": "Total Views", "value": 0},
      {"date": "2026-06-04", "type": "Total Views", "value": 2},
      {"date": "2026-06-05", "type": "Total Views", "value": 0},
      {"date": "2026-06-06", "type": "Total Views", "value": 0},
      {"date": "2026-06-07", "type": "Total Views", "value": 0},
      {"date": "2026-06-08", "type": "Total Views", "value": 0},
      {"date": "2026-06-09", "type": "Total Views", "value": 18},
      {"date": "2026-06-10", "type": "Total Views", "value": 50},
      {"date": "2026-06-11", "type": "Total Views", "value": 1},
      {"date": "2026-06-12", "type": "Total Views", "value": 12},
      {"date": "2026-06-13", "type": "Total Views", "value": 0},
      {"date": "2026-06-14", "type": "Total Views", "value": 108},
      {"date": "2026-06-15", "type": "Total Views", "value": 16},
      {"date": "2026-06-16", "type": "Total Views", "value": 38},
      {"date": "2026-06-17", "type": "Total Views", "value": 15},
      {"date": "2026-06-18", "type": "Total Views", "value": 11},
      {"date": "2026-05-31", "type": "Unique Views", "value": 0},
      {"date": "2026-06-01", "type": "Unique Views", "value": 1},
      {"date": "2026-06-02", "type": "Unique Views", "value": 0},
      {"date": "2026-06-03", "type": "Unique Views", "value": 0},
      {"date": "2026-06-04", "type": "Unique Views", "value": 1},
      {"date": "2026-06-05", "type": "Unique Views", "value": 0},
      {"date": "2026-06-06", "type": "Unique Views", "value": 0},
      {"date": "2026-06-07", "type": "Unique Views", "value": 0},
      {"date": "2026-06-08", "type": "Unique Views", "value": 0},
      {"date": "2026-06-09", "type": "Unique Views", "value": 1},
      {"date": "2026-06-10", "type": "Unique Views", "value": 4},
      {"date": "2026-06-11", "type": "Unique Views", "value": 1},
      {"date": "2026-06-12", "type": "Unique Views", "value": 2},
      {"date": "2026-06-13", "type": "Unique Views", "value": 0},
      {"date": "2026-06-14", "type": "Unique Views", "value": 1},
      {"date": "2026-06-15", "type": "Unique Views", "value": 1},
      {"date": "2026-06-16", "type": "Unique Views", "value": 1},
      {"date": "2026-06-17", "type": "Unique Views", "value": 1},
      {"date": "2026-06-18", "type": "Unique Views", "value": 1}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Views"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Git Clones for bcggxx/n0_kernel_pipa",
  "data": {
    "values": [
      {"date": "2026-05-31", "type": "Total Clones", "value": 1},
      {"date": "2026-06-01", "type": "Total Clones", "value": 0},
      {"date": "2026-06-02", "type": "Total Clones", "value": 1},
      {"date": "2026-06-03", "type": "Total Clones", "value": 1},
      {"date": "2026-06-04", "type": "Total Clones", "value": 3},
      {"date": "2026-06-05", "type": "Total Clones", "value": 0},
      {"date": "2026-06-06", "type": "Total Clones", "value": 2},
      {"date": "2026-06-07", "type": "Total Clones", "value": 6},
      {"date": "2026-06-08", "type": "Total Clones", "value": 3},
      {"date": "2026-06-09", "type": "Total Clones", "value": 87},
      {"date": "2026-06-10", "type": "Total Clones", "value": 34},
      {"date": "2026-06-11", "type": "Total Clones", "value": 1},
      {"date": "2026-06-12", "type": "Total Clones", "value": 0},
      {"date": "2026-06-13", "type": "Total Clones", "value": 1},
      {"date": "2026-06-14", "type": "Total Clones", "value": 89},
      {"date": "2026-06-15", "type": "Total Clones", "value": 44},
      {"date": "2026-06-16", "type": "Total Clones", "value": 15},
      {"date": "2026-06-17", "type": "Total Clones", "value": 57},
      {"date": "2026-06-18", "type": "Total Clones", "value": 9},
      {"date": "2026-05-31", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-01", "type": "Unique Clones", "value": 0},
      {"date": "2026-06-02", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-03", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-04", "type": "Unique Clones", "value": 2},
      {"date": "2026-06-05", "type": "Unique Clones", "value": 0},
      {"date": "2026-06-06", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-07", "type": "Unique Clones", "value": 6},
      {"date": "2026-06-08", "type": "Unique Clones", "value": 3},
      {"date": "2026-06-09", "type": "Unique Clones", "value": 44},
      {"date": "2026-06-10", "type": "Unique Clones", "value": 24},
      {"date": "2026-06-11", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-12", "type": "Unique Clones", "value": 0},
      {"date": "2026-06-13", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-14", "type": "Unique Clones", "value": 40},
      {"date": "2026-06-15", "type": "Unique Clones", "value": 28},
      {"date": "2026-06-16", "type": "Unique Clones", "value": 9},
      {"date": "2026-06-17", "type": "Unique Clones", "value": 32},
      {"date": "2026-06-18", "type": "Unique Clones", "value": 6}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Clones"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```

| Referral Source | Views | Unique Visitors |
|-|-|-|
| github.com | 61 | 2 |

### bcggxx/NonGKI_Kernel_Build_2nd

[![GitHub Repo](https://img.shields.io/badge/-Repository-white?logo=github&logoColor=181717&style=social)](https://github.com/bcggxx/NonGKI_Kernel_Build_2nd)&nbsp;
[![GitHub Stars](https://img.shields.io/github/stars/bcggxx/NonGKI_Kernel_Build_2nd?style=social)](https://github.com/bcggxx/NonGKI_Kernel_Build_2nd/stargazers)&nbsp;
[![GitHub Forks](https://img.shields.io/github/forks/bcggxx/NonGKI_Kernel_Build_2nd?style=social)](https://github.com/bcggxx/NonGKI_Kernel_Build_2nd/network/members)&nbsp;
[![GitHub Watchers](https://img.shields.io/github/watchers/bcggxx/NonGKI_Kernel_Build_2nd?style=social)](https://github.com/bcggxx/NonGKI_Kernel_Build_2nd/watchers)


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Visitors for bcggxx/NonGKI_Kernel_Build_2nd",
  "data": {
    "values": [
      {"date": "2026-06-01", "type": "Total Views", "value": 0},
      {"date": "2026-06-02", "type": "Total Views", "value": 0},
      {"date": "2026-06-03", "type": "Total Views", "value": 0},
      {"date": "2026-06-04", "type": "Total Views", "value": 5},
      {"date": "2026-06-05", "type": "Total Views", "value": 0},
      {"date": "2026-06-06", "type": "Total Views", "value": 0},
      {"date": "2026-06-07", "type": "Total Views", "value": 4},
      {"date": "2026-06-08", "type": "Total Views", "value": 0},
      {"date": "2026-06-09", "type": "Total Views", "value": 82},
      {"date": "2026-06-10", "type": "Total Views", "value": 128},
      {"date": "2026-06-11", "type": "Total Views", "value": 17},
      {"date": "2026-06-12", "type": "Total Views", "value": 3},
      {"date": "2026-06-13", "type": "Total Views", "value": 11},
      {"date": "2026-06-14", "type": "Total Views", "value": 34},
      {"date": "2026-06-15", "type": "Total Views", "value": 23},
      {"date": "2026-06-16", "type": "Total Views", "value": 16},
      {"date": "2026-06-17", "type": "Total Views", "value": 67},
      {"date": "2026-06-18", "type": "Total Views", "value": 3},
      {"date": "2026-06-01", "type": "Unique Views", "value": 0},
      {"date": "2026-06-02", "type": "Unique Views", "value": 0},
      {"date": "2026-06-03", "type": "Unique Views", "value": 0},
      {"date": "2026-06-04", "type": "Unique Views", "value": 1},
      {"date": "2026-06-05", "type": "Unique Views", "value": 0},
      {"date": "2026-06-06", "type": "Unique Views", "value": 0},
      {"date": "2026-06-07", "type": "Unique Views", "value": 1},
      {"date": "2026-06-08", "type": "Unique Views", "value": 0},
      {"date": "2026-06-09", "type": "Unique Views", "value": 1},
      {"date": "2026-06-10", "type": "Unique Views", "value": 2},
      {"date": "2026-06-11", "type": "Unique Views", "value": 2},
      {"date": "2026-06-12", "type": "Unique Views", "value": 3},
      {"date": "2026-06-13", "type": "Unique Views", "value": 1},
      {"date": "2026-06-14", "type": "Unique Views", "value": 1},
      {"date": "2026-06-15", "type": "Unique Views", "value": 1},
      {"date": "2026-06-16", "type": "Unique Views", "value": 1},
      {"date": "2026-06-17", "type": "Unique Views", "value": 1},
      {"date": "2026-06-18", "type": "Unique Views", "value": 2}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Views"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Git Clones for bcggxx/NonGKI_Kernel_Build_2nd",
  "data": {
    "values": [
      {"date": "2026-06-01", "type": "Total Clones", "value": 0},
      {"date": "2026-06-02", "type": "Total Clones", "value": 0},
      {"date": "2026-06-03", "type": "Total Clones", "value": 0},
      {"date": "2026-06-04", "type": "Total Clones", "value": 2},
      {"date": "2026-06-05", "type": "Total Clones", "value": 1},
      {"date": "2026-06-06", "type": "Total Clones", "value": 3},
      {"date": "2026-06-07", "type": "Total Clones", "value": 24},
      {"date": "2026-06-08", "type": "Total Clones", "value": 0},
      {"date": "2026-06-09", "type": "Total Clones", "value": 58},
      {"date": "2026-06-10", "type": "Total Clones", "value": 78},
      {"date": "2026-06-11", "type": "Total Clones", "value": 11},
      {"date": "2026-06-12", "type": "Total Clones", "value": 1},
      {"date": "2026-06-13", "type": "Total Clones", "value": 21},
      {"date": "2026-06-14", "type": "Total Clones", "value": 9},
      {"date": "2026-06-15", "type": "Total Clones", "value": 13},
      {"date": "2026-06-16", "type": "Total Clones", "value": 26},
      {"date": "2026-06-17", "type": "Total Clones", "value": 159},
      {"date": "2026-06-18", "type": "Total Clones", "value": 10},
      {"date": "2026-06-01", "type": "Unique Clones", "value": 0},
      {"date": "2026-06-02", "type": "Unique Clones", "value": 0},
      {"date": "2026-06-03", "type": "Unique Clones", "value": 0},
      {"date": "2026-06-04", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-05", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-06", "type": "Unique Clones", "value": 3},
      {"date": "2026-06-07", "type": "Unique Clones", "value": 4},
      {"date": "2026-06-08", "type": "Unique Clones", "value": 0},
      {"date": "2026-06-09", "type": "Unique Clones", "value": 24},
      {"date": "2026-06-10", "type": "Unique Clones", "value": 23},
      {"date": "2026-06-11", "type": "Unique Clones", "value": 5},
      {"date": "2026-06-12", "type": "Unique Clones", "value": 1},
      {"date": "2026-06-13", "type": "Unique Clones", "value": 6},
      {"date": "2026-06-14", "type": "Unique Clones", "value": 6},
      {"date": "2026-06-15", "type": "Unique Clones", "value": 7},
      {"date": "2026-06-16", "type": "Unique Clones", "value": 11},
      {"date": "2026-06-17", "type": "Unique Clones", "value": 26},
      {"date": "2026-06-18", "type": "Unique Clones", "value": 5}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Clones"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```

| Referral Source | Views | Unique Visitors |
|-|-|-|
| github.com | 37 | 1 |

