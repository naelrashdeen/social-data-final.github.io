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

# Analyzing the impact of wildfires in Galicia

To build a foundation for exploring historical ramifications of wildfire incidents in Galica we’re utilizing data collected over decades. In figure 4 we’ve mapped out wildfire causing significant destruction of above 100 hectares. While showing individual incidents (hover over for details) the data also clearly correlates previous figures. We can for instance infer from this that while Ourense has a very high amount of wildfire incidents the subregion is less plagued by severe mass wildfire spread. (fig 2, 3, 3.1).

<iframe src='visuals/4_map_galicia.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 4: </b>Geospatial map illustrating historical wildfires in Galicia which burned more than 100 ha area.</p>

Digging a bit deeper, Figure 5 illustrates a new measure of wildfire severity - Fire Radiative Power (FRP) in megawatts. FRP is the most effective indicator for analyzing fire severity in comparison to e.g., brightness. It is a direct measure of the radiant heat energy released. The heatmap reveals not just the geospatial points, but the intensity of fires regardless of burnt area - showcasing regions where wildfires with high intensity.

<iframe src='visuals/5_heatmap_galicia.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 5: </b>Heatmap of wildfire severity in Galicia from 2001-2022, categorized by Fire Radiative Power (FRP) in megawatts, illustrating areas with low, medium, and high wildfire intensity.</p>

In the heat of the Galician summers, where the frequency and intensity of the wildfires peak, so does the carbon footprint. This is illustrated in Figure 6, where the drastic spikes in CO2 emissions emerge during July - September. The figure shows a distinct seasonal pattern with low emissions during the cooler and wet months and escalates as temperatures rise and conditions become dry.

<iframe src='visuals/6_polarplot.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 6: </b>Polar-plot displaying the monthly distribution of CO2 emissions from wildfires in Galicia from 2002-2023, highlighting the peak emissions during the summer months.</p>

To understand the ramifications of the CO2 emissions in the summer months, it becomes crucial to understand the broader spectrum of pollutants released. **Figure 7** shows the various pollutants released, measuring the monthly distribution of wildfires. Pollutants such as Total Particulate Matter (TPM), Particulate Organic Compounds (PM25,OC) and gasses like Nitrogen Oxides (NOx) and Sulfur Dioxide (SO2) each contribute to the environmental degradation and has implications for air quality and public health. Notably, we see the significant spikes in emissions during the peak wildfire months of June - August, reflecting the trends seen in the polar plot above.

<iframe src='visuals/7_horizontal_other_polutants.html' style="border-width: 0px;" width="100%" height="850px"></iframe>
<p style="text-align: center;"> <b>Figure 7: </b>Horizontal bar chart showing the monthly distribution of emissions from pollutants released by wildfire incidents, detailing the total emissions in metric tons per month for pollutants like CO, CH4, NOx, and others.</p>

As we delve deeper into the features influencing wildfire occurrences in Galicia, we now transition our analysis from fire-related emissions to climate conditions that further cultivate such events. **Figure 9** shows us a correlation matrix, mapping out weather parameters directly influence the number of fire incidents reported.

Building on top of our previous visualizations the correlation matrix offers an understanding into several weather factors, such as temperature and vapour pressure. We see a positive correlation between higher temperatures and increased fire alerts, underpinning the role of weather features in worsening wildfire risks. On the other hand, it is also notable that higher humidity appears to have an inverse effect - reducing the likelihood of fire alerts as seen in the matrix.

<img src='images/9_correlation.png' alt="Correlation" />
<p style="text-align: center;"> <b>Figure 9: </b>Correlation matrix displaying the relationship between fire alert counts and various weather parameters such as temperature, humidity, precipitation, and solar radiation - color intensities indicate the strength of correlation.</p>

<iframe src='visuals/12_Irreplaceability_score_rank_map.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 12: </b>Chloropleth map of Galicia, showing ecological irreplaceability scores for various grid cells, based on criteria from the IUCN Red List and World Database on Protected Areas. The scores range from 0.2 to 0.9, with darker shades indicating higher irreplaceability.</p>

<iframe src='visuals/13_Aggregated_fire_risk_map.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 13: </b>Chloropleth map of Galicia, showing aggregated wildfire risk as a percentage of higher-risk areas in each cell. The gradient from light to dark red indicates increasing wildfire risk, based on modeling from the Copernicus Emergency Management Service.</p>

# References
