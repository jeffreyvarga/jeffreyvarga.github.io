---
layout: page
title: UFO Sightings in California
description: Quantitative Spatial Statistical Analysis of UFO Sightings in California
img: assets/img/UFO/UFO_Cover.png
importance: 6
category: work
related_publications: false
---
The full project report can be found here:

<a href="/workspaces/jeffreyvarga.github.io/assets/pdf/California_UFOSightings_ReportVarga.pdf" download>
    Download the report (PDF) 
</a>

<hr>

This project explored the spatial and temporal patterns of reported UFO sightings in California using point pattern analysis and GIS workflows in R. Leveraging a large dataset from the National UFO Reporting Center with over a century of observations, the analysis focused on two primary questions: whether UFO sightings exhibit spatial correlation with airports and military bases, and whether sightings vary meaningfully by season. California was selected as the study area due to its high concentration of observations and significant aviation and military presence.

The workflow involved extensive data preprocessing, including filtering, spatial transformation to the California Albers coordinate system, and conversion between tabular, sf, and spatstat-compatible formats. Multiple spatial analysis techniques were applied, including kernel density estimation, Ripley’s K and L functions, and average nearest neighbor analysis. These methods consistently indicated strong spatial clustering of UFO sightings rather than random dispersion. Visual comparison with airport locations suggested a clear spatial association, likely reflecting both aircraft activity and population distribution. Seasonal analysis showed relatively even distribution of sightings throughout the year, with no compelling evidence of seasonal influence.

Despite challenges related to data structure and methodological constraints, the project successfully demonstrates applied spatial statistics, geospatial data integration, and critical interpretation of results. Overall, the work highlights practical experience with point pattern analysis, spatial reasoning, and adapting analytical approaches when real-world data limit ideal methodologies.