---
layout:      project
title:       Crowd Viewer
date:        2023-01-01
image:
  path:       /assets/img/projects/crowdviewer/overview.png
  srcset:
    1920w:   /assets/img/projects/crowdviewer/overview.png
    960w:    /assets/img/projects/crowdviewer/overview.png
    480w:    /assets/img/projects/crowdviewer/overview.png
caption:     A Shiny dashboard showing Wifi connection count on campus.
description: >
  A Shiny dashboard showing Wifi connection count on campus.
links:
  - title:   Demo
    url:     https://caesarwong.shinyapps.io/campus-wifi-connection-count-dashboard/
  - title:   Source
    url:     https://github.com/caesarw0/crowd-viewer
featured:    false
---


The data dashboard is on Shinyappio.com ([Dashboard URL](https://caesarwong.shinyapps.io/campus-wifi-connection-count-dashboard/)).

## Dashboard Description

The dashboard is built using R Shiny (web), leaflet (map), and Plotly (data visualization). It provides information about the crowd data in the Hong Kong Polytechnic University with an interactive map. The application covers the Wifi connection data from May 1, 2019 to Oct 31, 2019. The data is taken in a 10 mins intervals per record.

### Overview

![overview](/assets/img/projects/crowdviewer/overview.png)

#### KPI on the top row

![toprow](/assets/img/projects/crowdviewer/datacard.png)
The data card shown in the top row listed the KPI in the selected filtering date period. Information includes total record count, unique device count, most frequent building, etc.

Two pages are showing the data in a different dimensions.

### 6 months tab

The slider bar selection is aggregated per day. Click the building block on the map to show statistics in the particular building.

![6month](/assets/img/projects/crowdviewer/6month_steps.png)

#### Dashboard Usage

1. Drag the slider bar to filter the data in a specific period, or drag the start and end date.

2. In the dropdown menu, select the desired color scheme for the map.

3. Click one of the building blocks for the click-by-building data to refresh the chart.

4. The line chart and bar chart is updated as per request by clicking the building block on the map.

5. The overview data showing the total record count and top 10 frequently connected buildings in the filtered DateTime.

### 1-day tab

Users can filter the data on a specific date within the 6 months period. The slider bar selection is aggregated per 10 mins. Click the building block on the map to show statistics in the particular building.

## File Structure

```bash
│   .gitignore
│   app.R               # main Shiny application script
│   building.dbf        # map related files
│   building.geojson    # map related files
│   building.prj        # map related files
│   building.shp        # map related files
│   building.shx        # map related files
│   README.md
│
├───focusGroupStudent   # data folder
│       df_allStudent.csv
│
├───server              # server folder
│       tab_1day.R
│       tab_6months.R
│
├───ui                  # ui folder
│       polyu.jpg
│       tab_1day.R
│       tab_6months.R
│
└───www                 # image folder
        logo3.png
        polyu.jpg
        polyu2.png
```

## Dependencies

- shiny==1.7.2
- shinyjs==2.1.0
- shinydashboard==0.7.2
- shinythemes==1.2.0
- shinycssloaders==1.0.0
- sqldf==0.4.11
- summarytools==1.0.1
- scales==1.2.1
- tidyverse==1.3.2
- ggplot2==3.4.0
- dplyr==1.0.9
- magrittr==2.0.3
- ggrepel==0.9.2
- plotly==4.10.1
- RColorBrewer==1.1.3
- rgdal==1.6.3
- leaflet==2.1.1
- htmltools==0.5.3
