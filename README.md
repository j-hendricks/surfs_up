# surfs_up
Using Python, Jupyter Notebook, SQLite, Flask

## Overview

In Oahu Hawaii, we have proposed to open a "Surf n' Shake" store that will sell surfing equipment and ice cream. In order to receive financial support from investors, we have to confirm that the weather in Oahu is usually warm and sunny. In other words, the average temperature in the summer needs to be near 70 degrees, and there cannot be frequent rain falls. 

The data was loaded into jupyter notebook from a SQLite database. From there, the data was analyzed, and then uploaded to a customized webpage using flask.

## Results

Below are the statistics for June and December temperatures. The histograms illustrate that the majority of temperatures are within 65-85 degrees, which is just what we will need for the ice cream shop. Since this data is based on over a 1,000 observations made over several year, we can trust that this data is reliable and will remain this way for years to come. 

### June Data

![summary_june](summary_june.png)

![hist_june](hist_june.png)

### December Data

![summary_dec](summary_dec.png)

![hist_dec](hist_dec.png)

### Flask

Here is a screenshot of the homepage. If the precipitation extention is added to the browser, the webpage containing the precipitation data is opened. 

![homepage](homepage.png)

![precipitation](precipitation.png)

## Conclusion

From the data collected, the "Surf n' Shake" is almost a guaranteed success. The temperatures are warm even in the winter season, and the rain will rarely dampen the store's success. 
