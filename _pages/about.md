---
layout: about
title: About
permalink: /
subtitle: <p><strong>GIS and Piano</strong>

profile:
  align: right
  image: prof_pic2.JPEG
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Located in Corvallis, OR</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
GIS Analyst experienced in municipal planning support, housing needs analysis, and applied spatial modeling for public-sector decision-making. Experienced in spatial analysis, network modeling, geospatial data management, and cartographic communication. Produces GIS outputs that translate complex datasets into actionable insights for planners, advisory committees, and stakeholders in Oregon land use contexts. 

<hr>

Hello! my name is Jeffrey Varga. I am a recent graduate of Oregon State University with a degree in Geospatial Science, alongside a completed degree in Piano Performance. I also hold GIS certifications, reflecting a focused and applied background in geospatial analysis.

My interest in GIS began through an introductory cartography course and quickly developed into a central academic and professional focus. Since then, I have built experience across spatial modeling, remote sensing, network analysis, 3D visualization, and Web GIS, with an emphasis on integrating complex datasets and developing structured analytical workflows.

Professionally, I have worked as a GIS Analyst with the City of Eugene Planning and Development Department, where I supported municipal planning through spatial analysis, data management, and applied research. My work included developing a network dataset in ArcGIS Network Analyst to evaluate housing accessibility, integrating housing and demographic datasets for contextualized housing need analysis, and performing quality control on the City's Historic and Cultural Resources database.

My project work further reflects this applied focus. Recent projects include modeling dust dispersion from the shrinking Great Salt Lake using LiDAR and atmospheric data, and conducting network-based evacuation analysis to identify optimal vertical evacuation structure locations for the Ocean Shores community in Washington.

Outside of GIS, I am a classically trained pianist with extensive solo and collaborative performance experience. I am also an Eagle Scout and a recipient of the Vigil Honor.

<hr>

<section class="highlighted-projects mt-5">

  <h2 class="section-heading">Selected Projects</h2>
  <p class="section-subheading">
    A few recent projects of mine.
    <a href="{{ '/projects/' | relative_url }}">See all projects →</a>
  </p>

  <div class="hp-grid">

    <!-- ── PROJECT 1 — replace with your real project ── -->
    <article class="hp-card">
      <img src="{{ '/assets/img/CHN/CHN_Cover.png' | relative_url }}"
           alt="Project 1 screenshot"
           class="hp-card__img" />
      <div class="hp-card__header">
        <span class="hp-tag">network analysis</span>
        <span class="hp-tag">Urban Planning</span>
      </div>
      <h3 class="hp-card__title">Housing Accessibility Network Model</h3>
      <p class="hp-card__desc">
        Developed a network dataset in ArcGIS Network Analyst to evaluate
        housing accessibility across Eugene, integrating housing and
        demographic datasets for contextualized planning analysis.
      </p>
      <div class="hp-card__footer">
        <a href="{{ '/projects/CHN/' | relative_url }}"
           class="hp-btn hp-btn--primary">
          <i class="fa-solid fa-arrow-right" style="font-size:12px;"></i>
          Read more
        </a>
      </div>
    </article>

    <!-- ── PROJECT 2 — replace with your real project ── -->
    <article class="hp-card">
      <img src="{{ '/assets/img/GSL/GSL_Cover.png' | relative_url }}"
           alt="Project 2 screenshot"
           class="hp-card__img" />
      <div class="hp-card__header">
        <span class="hp-tag">spatial modeling</span>
        <span class="hp-tag">LiDAR</span>
        <span> class="hp-tag">remote sensing</span>
      </div>
      <h3 class="hp-card__title">Great Salt Lake Dust Dispersion Model</h3>
      <p class="hp-card__desc">
        Modeled dust dispersion from the shrinking Great Salt Lake using
        LiDAR and atmospheric data interpolation to assess health and
        environmental risk across surrounding communities.
      </p>
      <div class="hp-card__footer">
        <a href="{{ '/projects/GSL/' | relative_url }}"
           class="hp-btn hp-btn--primary">
          <i class="fa-solid fa-arrow-right" style="font-size:12px;"></i>
          Read more
        </a>
      </div>
    </article>

  </div><!-- /.hp-grid -->

</section>