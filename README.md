# Programming for Data Analysis Project (2)

### By Joanne Feeney
***

### Introduction

For this project, I will:

- Analyse CO2 vs Temperature Anomaly from 800kyrs – present. 
- Examine one other (paleo/modern) features (e.g. CH4 or polar ice-coverage).
- Examine Irish context e.g. Climate change signals: (see Maynooth study: The emergence of a climate change signal in long-term Irish meteorological observations - ScienceDirect).
- Fuse and analyse data from various data sources and format fused data set as a pandas dataframe and export to csv and json formats.
- For all of the above variables, analyse the data, the trends and the relationships between them (temporal leads/lags/frequency analysis).
- Predict global temperature anomaly over next few decades (synthesise data) and compare to published climate models if atmospheric CO2 trends continue.
- Comment on accelerated warming based on very latest features (e.g. temperature/polar-icecoverage).
***

### Jupyter Notebook

First I import all the packages required for my investigations.

Then I read in the composite Co2 and full temperature datasets and drop any unrequired columns.

Using .info, .describe and .isnull functions to get an idea of what the dataset looks like. Re-naming the columns to a more readable format.

Plotting of the full Co2 dataset and then the last 50 years to see what the Co2 levels in the atmosphere have been for the last 800,000 years.

From the above, we can see that the levels of Co2 in the atmosphere has significantly increased in comparison to any amount of time in the past 800,000 years. The highest Co2 levels we have previously seen on this planet according to this dataset sat at about the 300 mark roughly 330,000 years ago whereas between 1950-present day we have gone way over this maximum and are now sitting at roughly 375.

Plotting temperature data.

Then, a plot with both Co2 and temperature data on the one graph.

As we can see in the plot, temperature and Co2 levels have stayed fairly consistant with one another over the last 800,000 years. It is quite difficult to see the blue line representing Co2 in place as the red line representing temperature overlays it however we can see that in recent years, both Co2 levels and temperature and strikingly higher that at any point in the last 800,000 years.
***

The one other feature that I investigate as part of this project will be polar ice coverage. I will do so by plotting data that I have located online.

I add a plot of ice mass loss in Antarctica 1992-2014.

Between 1992 & 2014 there has been a massive loss of ice in Antarctica, almost 1600 Gigatonnes lost in Antarctica alone. 

1992 was only 32 years ago and when we compare the rate of loss, this is highly concerning as we are all aware that the more polar ice that melts, the higher the sea levels and all other consequences that come with this massive change to the amount of water on our planet.

This dataset also provides data for loss of ice mass in Greenland, which I  have not plotted, as I am only investigating polar ice loss however shows an even greater disappearance of ice.

Then, investigating another dataset, sea ice from 1978-present (Northern Hemisphere).

From the sea ice in the Northern Hemisphere (NH) data, there is a great loss in millions of square kilometres (msk). In 1978, there was 12.328 msk of sea ice compared to 2023, when there was only 10.327 msk. 

Considering we are speaking about **millions** of square kilometres, that is a massive loss of sea ice. I can only imagine ehat this might mean for the species that live in these areas in the NH. That is a massive loss of habitat for them and will contribute majorly to their decline in numbers and possibly even exctinction if this rate of decline continues. 
***

For the Irish context, I read: 

Murphy et al., 2023, "The emergence of a climate change signal in long-term Irish meteorological observations" (https://www.sciencedirect.com/science/article/pii/S2212094723000610#bib13) 

I have also dowloaded the long-term dataset for Markree (in my home County of Sligo) from met.ie in order to see what temperature anomolies there are when comparing almost 200 yeras worth of data for our small island.

I have created plots of maximum temperatures in Markree 1850-1968, maximum temperature Markree on July 1st 1850-1968, maximum temperature Sligo Airport on July 1st 1988-2016 & maximum temperature Markree in July 2005-2023.

As we can see on the more recent data, July is now seeing a higher max temperature compared to preious years of 29C. The lowest max temperature of 20C is also way higher that the long term datasets lowest point, which was 12C.

I believe that the data I am investigating above shows us that for Ireland (and specifically Sligo alone), we are seeing a great increase in air temperatures compared to a couple hundres years ago. Considering that Co2 data that we have plotted at the very beginning is for 800,000 years, the vast changes we see in not even 300 years worth of data does not bode well for how quickly our planet is warming.
***

I have now fused all global data together and also fused all Irish data together and exported them to both csv and JSON formats.
***

## Conclusion

In conclusion, this Jupyter notebook aimed to analyse Co2, temperature & polar ice cover from 800kyrs – present. Through the course of the analysis, I have explored golbal Co2 levels, temperature for Ireland specifically and ice cover for Antarctica and the Northern Hemisphere. The data revealed some worrying trends in recent years for a stark increase of levels of Co2 in our atmosphere and high temperatures. These high temperatures are most likely what is contrubuting to the loss of ice coverage that I have investigated and plotted in figures in this notebook.

One of the notable aspects of this project was the fusing of different datasets from varied sources. Addressing this required much use of google and websites such as Stackoverflow.com, where the data analysis community have assisted other with similar queries or issues with code that I came across as part of my work.

Additionally, I will need to complete some future work to synthesise and predict temperature anomoly for the next few decades as I believe this level of python coding knowledge may be harder than I initially thought it would be. This project hopefully serves as a foundation for further exploration into the different factors that are changing our planet.
***

# The End