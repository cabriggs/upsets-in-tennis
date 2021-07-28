## Files included

tennis\_singles\_atp.zip: the ATP (men's) data
tennis\_singles\_wta.zip: the WTA (women's) data
upsets-in-tennis-report.pdf: a report summarizing the study's findings
upsets-in-tennis-slides.pdf: a collection of data visualizations from the study
upsets-in-tennis.ipynb: a Jupyter notebook containing the analysis and narrative.

## Background

Tennis players are ranked from #1 (best) to the hundreds. In order to measure upsets (in which a lower-ranked player beats a higher-ranked player), and quantify the extent of upset, we may compute the winner's rank minus loser's rank in a tennis match.

## Problem statement

Are upsets more common in women's tennis than men's? Are upsets equally likely across the three main court surfaces (clay, grass, hard)?

## What data

I have data showing the outcome of every match at every ATP tournament from 1981 onwards, and 1986 onwards for the WTA.

## What methods

I compute the above mentioned statistic (winner's rank minus loser's rank), then conduct hypothesis testing on the mean for this statistic across the mentioned categories.

### Technology

The analysis was performed in a Jupyter notebook, leveraging the pandas, numpy, scipy, and thinkplot libraries.

## What conclusions

Upsets are most likely on clay courts and least likely on grass courts. There is no statistically significant difference in upsets between men's and women's tennis.

## What questions remain

Is there a statistic which more accurately captures the tendency of upsets? The used statistic works, but fails to differentiate between e.g. world #241 defeating #201, and world #41 defeating #1. The latter is certainly less likely.
