---
layout: page
title: GSL Dust Transport Regime
description: Dust Transport Regimes and Public Health Implications at the Great Salt Lake
img: assets/img/GSL/GSL_Cover.png
importance: 1
category: work
related_publications: false
---
The full project report can be found here:

<a href="/workspaces/jeffreyvarga.github.io/assets/pdf/JeffreyVarga_FinalReport.pdf" download>
    Download the report (PDF) 
</a>

<hr>

Wind-blown dust from desiccating (evaporating) saline lakes is a growing environmental hazard. Globally, playas that formed after large lakes receded now release fine particulate matter rich in salts, toxic metals, and microbial contaminants. Saline terminal lakes are shrinking on every inhabited continent, and their newly exposed playas now rank among the most aggressive natural sources of atmospheric dust. These sediments are typically alkaline, highly erodible and enriched in trace metals, so their mobilization threatens respiratory health, water security, and regional economies. Utah’s Great Salt Lake (GSL) is a prominent case. Surface withdrawals and twenty-five years of persistent drought have lowered the lake to its historic minimum, unveiling more than 800 mi² (≈2 070 km²) of lakebed that is intermittently entrained by strong synoptic winds.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GSL/Fig. 2 Overview.png" title="GSL dust overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the study area, included the dust-prone region (see below for details).
</div>

The desiccation of Utah’s Great Salt Lake exposes fine, metal‐rich sediments that pose respiratory health risks when mobilized by wind. In recent years, this has become an increasingly important issue. The Great Salt Lake’s shrinking exposes toxic, metal-rich sediments that wind can carry into nearby communities, posing a public-health crisis by exacerbating asthma, COPD and other respiratory illnesses. Pinpointing the most active dust-source areas is therefore vital to directing mitigation efforts and protecting vulnerable populations. 

By combining remote sensing, atmospheric modeling, and public‐health data, I isolated the lakebed areas most prone to harmful dust emissions and assess their correlation to health impacts to downwind population centers. I derived a Dry Bare Soil Index and two other spectral reflectance indices from Landsat 8–9 imagery, calibrating thresholds to map dust‐prone polygons. Wind speed and wind direction measurements at 100m, 500m, and 1,000m elevations were aggregated into a master dataset and interpolated through Empirical Bayesian Kriging 3D to create continuous voxel layers.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GSL/Fig. 5 Wind Both.png" title="Wind speed and direction voxels above 2D map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Empirical Bayesian Kriging 3D interpolation of wind measurements at 100m, 500m and 1,000m elevations produced these continuous voxel layers for speed and direction. Average annual wind speeds exceed 8 m/s across significant portions of the voxel volume. Additionally, nearly the entire voxel showcases wind approaching the 8 m/s threshold (6.5 – 8 m/s). The average annual wind direction 3D voxel, when limited to display directional values of only 180 to 360° (the direction that leads to the Wasatch Front), showed extreme clustering of values directly over the exposed lakebed and dust-prone region. 
</div>
<iframe width="800" height="600" frameborder="0" scrolling="no" allowfullscreen src="https://arcg.is/00WDfX"></iframe>
<div class="caption">
    Interactive web scene. 
</div>

<hr>

The layers with census tract asthma and COPD rates in ArcGIS Pro are used to evaluate spatial correlations. The analysis identifies roughly 1300 mi² (3350 km²), of exposed lakebed as a dominant likely dust source. Voxel modeling shows northwesterly winds frequently approaching and regularly exceeding 8 m/s nearby the dust region. Overlaying health data reveals that populations downwind exhibit notably higher asthma and COPD prevalence than upwind areas. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GSL/Fig. 3 Asthma.png" title="Wind speed and direction voxels above 2D map" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GSL/Fig. 4 COPD.png" title="Wind speed and direction voxels above 2D map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

These findings confirm that a small fraction of the lakebed drives most harmful dust emissions and that prevailing wind regimes deliver those emissions to densely populated corridors. The clear spatial correlation between modeled transport pathways and elevated respiratory rates emphasizes the public‐health significance of targeted dust‐suppression measures. Future work should involve integration with field validation PI-SWERL measurements, incorporation of seasonal or daily wind‐voxel time series, and refined spectral thresholds to reduce uncertainty and guide mitigation strategies.