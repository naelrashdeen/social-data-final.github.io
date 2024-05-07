---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Wildfires in Galicia
---

**Authors**: Nael Rashdeen, Ali Berk Gezgin, Joakim Wiben Gundersen

<p style="font-size: 16px;"><em>May 7, 2024</em></p>

# Introduction

Wildfires, historically a natural and integral part of many ecosystems, have been increasingly causing widespread destruction and are having a devastating impact on human settlements, economies and ecosystems alike. In Europe, this is particularly true in the Galicia region of Spain [Ref1](https://civio.es/en/spain-in-flames/forest-fires-map/), that have been identified as the most wildfire-prone area in Spain (see Figure 1).

<img src="images/1_fires_regions_Spain.png" alt="Wildfires in Galicia" />
<p style="text-align: center"><b>Figure 1: </b>Mean burned area and wildfire incidents per km2 by region in Spain (2002-2023) showing regional variations in fire severity and frequency</p>

Wildfires in Galicia are not merely coincidental - it is rooted in a combination of environmental, geographical and natural climatic factors. The regions hosts extensive forests, predominantly composed of highly flammable species such as pine and eucalyptus, and coupled with dry, rugged terrain the region has always been a hotbed for wildfire ignition and spread.

While natural factors have long influenced the wildfire regime in Galicia there have been an ever increasing rate of incidents - and the imprint of climate change is becoming increasingly evident. Rising temperatures, shifting precipitation patterns and periods of drought are currently being associated man-made climate change, which in turn are increasing the risk of wildfires (https://www.usgs.gov/science-explorer/climate/wildfire).

The combination of warmer and drier conditions not only prolongs the wildfire season in Galicia, but also enhances the likelihood of increased intensification of wildfires in the future (see Figure 2).

<img src='images/2_treeloss_galicia.png' alt="Tree Loss" />
<p style="text-align: center"> <b>Figure 2: </b>Annual tree cover loss in Galicia (Green), Spain from 2001 to 2023, distinguishing between total loss and loss specifically due to wildfires (Red), highlighting years with significant wildfire impact.</p>

This project will explore the role and frequency of wildfires in the region based on both historic and current data from multiple sources. We’re aiming to increase awareness for both locals, tourists and policy-makers by combining important datasets that have so far been scattered, visualizing them together and using the data as a base for predicting future events using machine learning - effectively increasing ease of access, and allowing stakeholders to take actions based on informed decisions.

# Hello

<div class="visuals">
    <div>
        <img src='images/3_piechart.png' alt="Pie-chart" />
    </div>
    <div>
        <img src='images/3.1_horizantalbars.png' alt="Bar-chart" />
    </div>
</div>
<div class="visuals-text">
    <div>
        <p style="text-align: center"> <b>Figure 3: </b>Distribution of tree cover across the subregions of Galicia with specific area measurements in hectares for each subregion. </p>
    </div>
    <div>
        <p style="text-align: center"> <b>Figure 3.1: </b>Total alerts by subregions of Galicia, illustrating the number of alerts reported in each subregion from highest to lowest.</p>
    </div>
</div>

<iframe src='visuals/4_map_galicia.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 4: </b>Geospatial map illustrating historical wildfires in Galicia which burned more than 100 ha area.</p>

<iframe src='visuals/5_heatmap_galicia.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 5: </b>Heatmap of wildfire severity in Galicia from 2001-2022, categorized by Fire Radiative Power (FRP) in megawatts, illustrating areas with low, medium, and high wildfire intensity.</p>

<iframe src='visuals/6_polarplot.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 6: </b>Polar-plot displaying the monthly distribution of CO2 emissions from wildfires in Galicia from 2002-2023, highlighting the peak emissions during the summer months.</p>

<iframe src='visuals/7_horizontal_other_polutants.html' style="border-width: 0px;" width="100%" height="850px"></iframe>
<p style="text-align: center;"> <b>Figure 7: </b>Horizontal bar chart showing the monthly distribution of emissions from pollutants released by wildfire incidents, detailing the total emissions in metric tons per month for pollutants like CO, CH4, NOx, and others.</p>

<!-- <img src='images/8_calendarplot.png' alt="CalendarPlot" />
<p style="text-align: center;"> <b>Figure 8: </b> </p> -->

<img src='images/9_correlation.png' alt="Correlation" />
<p style="text-align: center;"> <b>Figure 9: </b>Correlation matrix displaying the relationship between fire alert counts and various weather parameters such as temperature, humidity, precipitation, and solar radiation - color intensities indicate the strength of correlation.</p>

<img src='images/10_boxplots.png' alt="Box_Plots" />
<p style="text-align: center;"> <b>Figure 10: </b>Box plots displaying the distribution of key weather parameters including temperature, humidity, precipitation, wind speed, and solar radiation, which are crucial in understanding wildfire risks. Each plot represents the variability and outliers of the data collected.</p>

<iframe src='visuals/12_Irreplaceability_score_rank_map.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 12: </b>Chloropleth map of Galicia, showing ecological irreplaceability scores for various grid cells, based on criteria from the IUCN Red List and World Database on Protected Areas. The scores range from 0.2 to 0.9, with darker shades indicating higher irreplaceability.</p>

<iframe src='visuals/13_Aggregated_fire_risk_map.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 13: </b>Chloropleth map of Galicia, showing aggregated wildfire risk as a percentage of higher-risk areas in each cell. The gradient from light to dark red indicates increasing wildfire risk, based on modeling from the Copernicus Emergency Management Service.</p>

# References
