---
layout: page
title: Ocean Shores Proposed VES
description: Proposed Vertical Evacuation Options in Ocean Shores East, Wasington. In partnership with the State of Washington Emergency Management Division
img: assets/img/OSEast/OSEast_Cover.jpg
importance: 1
category: work
related_publications: false
---

The desiccation (evaporation) of Utah’s Great Salt Lake exposes fine, metal‐rich sediments that pose respiratory health risks when mobilized by wind. In recent years, this has become an increasingly important issue. The Great Salt Lake’s shrinking exposes toxic, metal-rich sediments that wind can carry into nearby communities, posing a public-health crisis by exacerbating asthma, COPD and other respiratory illnesses. Pinpointing the most active dust-source areas is therefore vital to directing mitigation efforts and protecting vulnerable populations. By combining remote sensing, atmospheric modeling, and public‐health data, I pinpoint the lakebed areas most prone to harmful dust emissions and assess their correlation to health impacts to downwind population centers. I derived a Dry Bare Soil Index and two other spectral reflectance indices from Landsat 8–9 imagery, calibrating thresholds to map dust‐prone polygons. Wind speed and wind direction measurements at 100m, 500m, and 1,000m elevations were aggregated into a master dataset and interpolated through Empirical Bayesian Kriging 3D to create continuous voxel layers. These layers with census tract asthma and COPD rates in ArcGIS Pro to evaluate spatial correlations. The analysis identifies roughly 1300 mi² (3350 km²), of exposed lakebed as a dominant likely dust source. Voxel modeling shows northwesterly winds frequently approaching and regularly exceeding 8 m/s nearby the dust region. Overlaying health data reveals that populations downwind exhibit notably higher asthma and COPD prevalence than upwind areas. These findings confirm that a small fraction of the lakebed drives most harmful dust emissions and that prevailing wind regimes deliver those emissions to densely populated corridors. The clear spatial correlation between modeled transport pathways and elevated respiratory rates emphasizes the public‐health significance of targeted dust‐suppression measures. Future work should involve integration with field validation PI-SWERL measurements, incorporation of seasonal or daily wind‐voxel time series, and refined spectral thresholds to reduce uncertainty and guide mitigation strategies.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
