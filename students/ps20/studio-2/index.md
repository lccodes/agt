Data involving the GNI and HDI of regions and their respective sub-regions was analyzed in order to determine which areas experience the highest standard of living (assuming this is captured in the HDI metric). The first analysis involved a breakdown of the average HDI by region and sub-region. The "=MAX(RANGE)" function was applied to determine the max avg. HDI per each region. These values were then presented graphically, as can be seen in the graphic below: 

![Average HDI by Region and Sub-Region](avg_hdi_region.png)

This analysis was continued with a breakdown of the HDI, specifically by mean years of schooling, mean life expectancy at birth, and mean GNI. 

![Distribution of Mean HDI, YOS, and LEAB](breakdown_HDI.png)

Mean GNI had most dramatic variance amongst the studied regions, so this metric was further analyzed. The median and mean value of GNI was recorded for each region, and these values were then compared using the "=IF(test, "X", "Y")" function. Surprisingly, various regions had a median GNI value that exceeded that same region's mean GNI value. Those regions are Northern and Southern Africa and Eastern, Northern, and Southern Europe. The "=Quartile(Range, X)" function was used to determine the quartiles of this data to determine its spread. The quartiles are as follows: 1 - 3690.5; 2 - 10667; 3 - 22800.5 ; 4 - 123124. 

The GNI was then plotted with HDI to observe their relationship. There appears to be a strong correlation between the two, suggesting that HDI is in large part determined by GNI. 

![GNI vs. HDI](gni_vs_hdi.png)



