# Spatial interpolation of particulate matter across Greater Sydney

Assignment as part of Statistical Thinking for Data Science subject

Full report available here https://github.com/Declan-Stockdale/PM10_anaysis_greater_sydney/blob/master/Spatial%20interpolation%20of%20particulate%20matter%20across%20Greater%20Sydney.pdf

## Overview
This project analysed the particualte matter sub 10um (PM10) across Greater Sydney using data from the https://www.dpie.nsw.gov.au/air-quality/air-quality-concentration-data-updated-hourly
This data was accessed using API calls from the dpei website and the Schools Weather and Air Quality (SWAQ) website which contained an additional 14 location in Sydney at the time of project completion.

As it's not feasible to measure the exact PM10 values at every point in Sydney estimations must be made instead. Two methods if estimation for the spatial interpolations were used, Inverse Distance weighing and Kriging.

Ordinary kriging, Universal kriging and Inverse Distance weighing were all assessed using leave one out cross validation due to the small number of stations


Map of air monitoring stations within Greater Sydney and surrounding areas

![image](https://user-images.githubusercontent.com/53500810/206881394-a20bd7c6-02bc-4f13-ac34-ebb6ab3bd449.png)


Generated variogram used for kriging procedure

![image](https://user-images.githubusercontent.com/53500810/206881352-9b3104fe-8c8a-4d4e-8e7a-c92576ae45ac.png)


