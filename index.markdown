---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: San Francisco, a focused crime story
---

**Date:** 2 April 2024
**Authors**: Nael Rashdeen - s144841 & Ali Berk Gezgin - s220006

San Francisco, a city known for its iconic Golden Gate Bridge, vibrant culture and Silicon Valley has long grappled with public safety challenges.

The “San Francisco Police Department Incident Reports” dataset encompasses a detailed record of crime incidents in San Francisco from January 2003 to May 2018. It includes a wide array of attributes that not only categorize each crime but also pinpoint its occurrence in time and location. The 'Category' attribute classifies the nature of the crime, covering a broad spectrum of crime types for the incidents. To provide temporal context, each record specifies the 'DayOfWeek,' 'Date,' and 'Time' of the incident. Furthermore, the geographical details are meticulously noted through the 'PdDistrict' attribute, which identifies the San Francisco district of occurrence, and 'X' and 'Y' coordinates, indicating the precise longitude and latitude. The dataset serves as a comprehensive resource for understanding crime patterns, distribution, and frequency across different districts in San Francisco, offering invaluable insights for the general public interested in the dynamics of urban safety.

Containing 32 unique categories of crime, the ground reality mirrors the challenges and societal shits that San Francisco has faced during the years. The high occurences of drug-related crimes along with incidents of larceny and burgulary shows us the disparity between wealth and poverty on the same blocks. Furthermore, instances of violent crime such as assault and robbery - punctuate the city's narrative with urgent calls and effective policing.

<iframe src='sf-focus-crime-incidents.html' style="border-width: 0px;" width="100%" height="400px"></iframe>
<p style="text-align: center;"> <b>Figure 1: </b> This interactive Bokeh Time Series plot shows the number of incident for the focused crime categories from 2003 - 2018 </p>

We focus on a particular set of crimes and hope to shed light on the specific challenges they represent. Our objective is to provide a data-driven analysis that not only quantifies the city's struggles with crime but also offers insights into the ground reality among the population.

The radial polar plot captures the 24-hour pattern of prostitution related crimes in San Francisco. Each bar on the wheel represents an hour of the day, and the length of each bar indicates the number of incidents reported at that particular time. From that it is immediately clear that this category of crime peaks in the late night to early morning hours of dawn.

<iframe src='sf-polar-plot.html' style="border-width: 0px; margin-left: 85px;" width="80%" height="400px"></iframe>
<p style="text-align: center;"><b>Figure 2: </b>The interactive radial polar plot illustrates the 24-Hour Cycle of Prostitution Crimes. The blue bars represent the count of prostitution crime incident for the relevant hour of the day and the lateral white numbers are there for indicating the level of frequency.</p>

From midnight to 5 AM, there is a noticeable surge in reported incidents and the nocturnal spikes align with the patterns of night-life acitivities - reflecting the increased vulnerability of night time workers. Alternatively, the plot shows a significant drop in reported incidents during daylight illustrating the cyclic nature of this illegal crime.

This dataset's analysis reveals that prostitution-related crimes in San Francisco notably spike during late-night and early-morning hours, indicating that such activities predominantly occur during these times. Supporting this finding, an article (Balakrishnan, Apr. 2024) highlights the challenges faced by the San Francisco community, particularly in the Shotwell Street area, where the closure of Capp Street to through traffic has inadvertently shifted the concentration of sex work and associated disturbances to neighbouring areas. Residents report increased traffic, safety concerns, and encounters with sex work directly outside their homes during late-night and early-morning hours, indicating a displacement effect rather than an elimination of the problem. This shift has not only brought traffic and noise but also heightened interactions involving sex workers and their clients during these specific hours, reflecting the dataset's findings on the timing of such crimes. The community's experience, characterized by the displacement of sex work to residential areas during the night, vividly illustrates the direct correlation between the timing of prostitution-related activities and the challenges faced in managing and mitigating their impact. This real-world example underscores the temporal and spatial fluctuations of prostitution-related crimes in urban settings, corroborating the dataset's findings with tangible community impacts and the challenges of addressing such issues through spatial interventions alone.

Transitioning from the dark hours where incidences of prositution are most common - we observe a shift in criminal activity as daylight ascends. The focus moves from individuals to possesions, particularly during the weekends and on Sundays - where the cholorpeth map offers a visual representation of areas with a heightened risk of vehicle theft. The choropleth map illustrates the risk of vehicle theft crime occurance for each district of San Francisco. Darker the red color means higher risk of vehicle theft in that district and vice versa.

Ingleside and it's neighbouring districts - Bayview and Mission, all have a darker red color on the map showcasing them to become hotspots for vehicle theft on sundays.

<iframe src='sf-vehicle-theft-sundays.html' style="border-width: 0px; margin-left: 85px;" width="100%" height="500px"></iframe>
<p style="text-align: center;"><b>Figure 3: </b>The interactive choropleth map illustrates the risk of vehicle theft crime occurance for each district of San Francisco. Darker the red color means higher risk of vehicle theft in that region and vice versa.</p>

This pattern in the data not only underscores the neighobouring communities to stay alert and vigilant but also indicates of a need for law and enforcement authorities to be more alert and present on certain days in certain districts.

According the sources indicate (Marcus, Dec. 2023) (Rezal and Caughey, Nov. 2023 ) compared to neighbouring provinces, motor vehicle theft tends to increase at incredible levels in San Francisco. The dataset's analysis revealing Ingleside as the district with the highest incidence of vehicle theft incidents is significantly corroborated by external sources, emphasizing the acute challenge this area faces regarding auto theft. According to a recent report (Lamb, Sept. 2023), the Ingleside Police Station, which oversees the Outer Mission, Ingleside, and Excelsior neighbourhoods, has experienced a staggering amount of stolen cars. This underscores the dataset's findings and also highlights the pressing issue of vehicle theft in the Ingleside district. This relationship between the dataset's findings and external reports serves as a crucial tool for understanding crime patterns and focusing resources effectively to combat such incidents in San Francisco's Ingleside district.

The analysis of the "San Francisco Police Department Incident Reports" dataset, enriched by corroborative external sources, brings to light the patterns of urban crime in San Francisco, from the prostitution-related activities in the nocturnal hours to the alarming rate of vehicle thefts in specific districts like Ingleside. These insights not only highlight the temporal and geographical nuances of criminal behaviour but also stress the importance of strategic community engagement efforts in addressing such challenges. As we conclude, it's evident that understanding and tackling of urban crime requires a comprehensive approach, leveraging detailed data analysis to inform and guide the community. This underscores the critical role of data in unveiling the dynamics of crime, paving the way for a safer urban environment.

# References

[1] Balakrishnan, Eleni. “SF “Playing Whac-A-Mole” with Sex Work on Capp, Shotwell.” Mission Local, 6 Dec. 2023, missionlocal.org/2023/12/sf-playing-whac-a-mole-prostitution/. Accessed 2 Apr. 2024.

[2] White , Marcus . “How SF Crime Trends Compare to the Rest of US.” San Francisco Examiner, 13 Dec. 2023, www.sfexaminer.com/news/crime/how-san-francisco-crime-trends-compare-to-drops-across-us/article_a23f638e-99de-11ee-a582-df313ac11b80.html. Accessed 1 Apr. 2024.

[3] Rezal, Adriana , and Erin Caughey. “Https://Www.sfchronicle.com/Projects/2022/Fixing-San-Francisco-Problems.” The San Francisco Chronicle, 5 Nov. 2022, www.sfchronicle.com/projects/2022/fixing-san-francisco-problems/crime.

[4] Lamb, Jonah Owen. “Stolen Cars: Over 15,000 Auto Thefts in San Francisco and Oakland This Year.” The San Francisco Standard, 26 Sept. 2023, sfstandard.com/2023/09/26/oakland-car-theft-spikes-san-francisco-bay-area-car-thefts-up-some/. Accessed 2 Apr. 2024.
