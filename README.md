# surfs_up

## Overview of the analysis

This analysis focuses on retrieving temperature data for the months of June and December in Oahu, to determine if a surf & ice cream shop business is sustainable year-round. The analysis uses Python, Pandas funcitons and methods, and SQLAlchemy, to filter the data column of the Measurements table in the hawaii.sqlite database.

## Results

- The average temperature in June (75 degrees) is only 4 degrees higher than that of December (71 degrees).
- The minimum temperure in June (64 degrees) is 8 degrees higher than that of December (56 degrees).
- The maximmume temperature in June (85 degrees) is 2 degrees higher than that of December (83 degrees)

### June Stats

<img src="/images/jun_temps.png">

### December Stats

<img src="/images/dec_temps.png">

## Summary

On average, the temperatures in December are not very different from the ones in June. The Dec temperatures are only about 4 degrees higher than those in June. For reference, 4 degrees is slighthly above 1 STD of the Dec and Jun temperatures (see chart with details in the "Results" section).

### For further analysis

To visualize the data, we could use matplotlib to plot the December and June temperatures. Note that there are about 200 more observations for June than for December data. However, we can still look at the center, spread, and shape of the data, and see that December is not that different from June.
<img src="/images/plot.png">
