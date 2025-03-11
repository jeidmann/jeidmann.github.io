---
layout: page
title: how pre-emptive fire treatment affects wildfires
description: Spatial and temporal analysis of the  Rodeo-Chediski fire using MODIS and Lansat imagery and vegetation regrowth (NDVI).
img: assets/img/wildfire.png
importance: 2
category: work
---

<h2>Analysis Description</h2>
As part of the Southwest Climate Adaptation Science Center, I took part in a collaborative research fellowship. Working with a group of 7 other fellows, we analyzed the relationship between fire and society. Throughout our analysis, we learned about the role that fire plays for ecosystem health and culture from the standpoint of indiginous people. We also applied a more quantitative assessment of climate change trends and the impacts of fire treatments. In this project, my main contribution was through analysis of the Rodeo-Chediski fire, where I analyzed the spatial and temporal impacts of pre-emptive perscribed burns as wildfire treatment techniques.

<h3>The Rodeo-Chediski Fire</h3>
The wildfire, which burned 462,600 acres between June 18 and July 7, 2002, was the culmination of two human-induced ignitions. The prolonged drought during that time period enhanced the spread of the fire across the Mogollon Rim; a high elevation and forested region of Arizona.

At the time of the fire, the Rodeo-Chediski fire was the largest and most destructive fire in Arizona's history.

Consequences of the fire include:

<ul>
    <li>Destruction of 500 homes, evacuation of 30,000 people.</li>
    <li>Decrease of soil infiltration rates up to 3 years post-fire, causing peak storm flows of historical magnitude.</li>
    <li>In high-severity burn areas, ~75% of pre-fire trees died within 3 years post-fire. </li>
    <li>Less than 5% of pre-fire trees died in areas of low-severity burns.</li>
</ul>

<div class="float-center mr-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/RodeoFire.png" caption="A postfire image from Landsat 5. The green colors indicate unburned or very lightly burned areas; red areas illustrate highly burned land." class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h3>A case study of prescribed burns</h3>
Forest treatment was practiced before the fire outbreak, allowing for a case study to evaluate the impact of prescribed burns on forest recovery post-fire.

<h4>Area of Analysis</h4>
In this analysis, I compare four areas of no fire treatment ('NoTreat 1-4') to four pre-fire prescribed burn areas ('Pre 1-4'). The prescribed burn areas are distinguished by their timing of fuel treatment before the fire. To evaluate differences, I applied remote sensing techniques.

<div class="float-center mr-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/FireTreat.png" caption="A map of the brightness index, showing areas of variable burn intensities, as well as the delineation of the different areas of analysis." class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>Comparing Burn Intensity</h4>
The 'Brightness Index' obtained from NASA's MODIS sensor can be used to extract burn severity. A higher 'Brightness Index' corresponds to a higher burn severity.

Analysis reveals an overall trend that treated areas (e.g. prescribed burn areas) are associated with a lower-severity burn than untreated areas. These results are supported by previous research (Finney et al., 2005; Strom and Fule, 2007).

<div class="float-center mr-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/BurnIntensity.png" caption="Generally, areas that received fire treatment before the fire were associated with a lower burn intensity than those areas that did not." class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>Comparing Vegetation Recovery Through the Normalized Difference Vegetation Index (NDVI)</h4>
The NDVI can provide insight into relative 'greenness' or vegetation health, with higher values generally indicating healthier vegetation.

A comparison of the relative proportion of area according to NDVI illustrates post-fire vegetation recovery.

Initially, areas with no fire treatment had a higher proportion of healthy vegetation (see 'Before Fire').

In the years following the fire (up to 9 years post-fire), treated areas ('Prescribed') consistently had a higher proportion of healthy vegetation.

This analysis suggests that prescribed burns are associated with lower-severity burns and therefore healthier vegetation in the long-term (>9 years).

<div class="float-center mr-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/NDVI_Comp.png" caption="A comparison of the distribution of NDVI values across areas with and without fire treatment. Whereas this distribution was relatively even before the fire, post-fire there is a higher proportion of higher NDVI values in areas that received fire treatment, indicating a lower burn severity and higher green-ness post-fire." class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>Comparing Post-Fire NDVI</h4>
On average, areas identified as 'Prescribed Burns' had healthier vegetation than areas without treatment.

The time since fire treatment, however, appears to make a difference. The average NDVI between areas treated 6-7 years pre-fire is not significantly different from those without fire treatments. Areas more recently treated (1-2 years pre-fire) have significantly higher average NDVI values. These conclusions are supported by Finney et al. (2005)'s findings.

<div class="float-center mr-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/NDVI_CHange.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>Changes in Landcover</h4>
Landcover Classification was extracted from MODIS Terra and Aqua reflectance data at 250m resolution, and categorized according to the IGBP classification. The proportion area covered by each land classification was compared across the 8 analyzed areas.

Across almost all analyzed areas, the fire caused an initial decrease in Savannas and increase in Grasslands.

Analyses reveal variability in the dominant land cover across 'Prescribed' vs. 'No Treatment' areas. Whereas fluctuations do occur in 'Prescribed' areas, the proportions of landcover type in these areas are comparable pre-fire and 9 years post-fire.

'No Treatment' areas show more long-term changes in landcover type. This is especially evident in 'No Treatment 4'--the area of highest burn intensity.

<div class="float-center mr-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Landcover.png" caption="Plots exhibiting changes in the dominant vegitation in the years since the fire across the areas of analysis. " class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<h4>References</h4>
Finney, M., McHugh, C., & Grenfell, I. (2005). Stand- and landscape-level effects of prescribed burning on two Arizona wildfires. Canadian Journal of Forest Research, 35(7).

Ffolliott, P., & Neary, D. (2003). Initial Assessment of the Rodeo-Chediski Fire Impacts on Hydrologic Processes. Hydrology and Water Resources in Arizona and the Southwest, 1–7.

Ffolliott, P., Stropki, C., Chen, H., & Neary, D. (2011). The 2002 Rodeo-Chediski Wildfire’s impacts on southwestern ponderosa pine ecosystems, hydrology, and fuels. U.S. Department of Agriculture, Forest Service, Rocky Mountain Research Station, 36.

Strom, B., & Fule, P. (2007). Pre-wildfire fuel treatments affect long-term ponderosa pine forest dynamics. International Journal of Wildland Fire, 16, 128–138.
