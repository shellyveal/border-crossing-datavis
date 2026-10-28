# Visualizing Border Crossings into the U.S.

## Employing data visualization packages in R to convey U.S. border entries between 1996 and 2019

Creating visual representations of border crossings of individuals into the United States between 1996 and 2019, excluding data that identifies chiefly the imports or crossings of non-persona. While this data focuses narrowly on **human** movement into the U.S., it does not include information on border crossings **exiting** from the U.S., nor does it distinguish among U.S. citizens and non-U.S. citizens. This project therefore does not pretend to make claims on the nature of permanent migration/resettlement.

## Chief Inquiries

This project seeks to employ R packages to identify human border crossings into the U.S. across border states between 1996 and 2019, with main questions including:

- What is the overall trend in U.S. entries over land borders?
- Which border entry locations are busiest/allow the largest flow of migrants?
- In which years/seasons are the border crossings at their highest?
- Are there visible changes in the residuals over time marking historic changes in migration (e.g. post-9/11 crackdowns)?
- How do entry rates on the Canadian border compare to those of the Mexican border?

## R Visualization Packages

Chiefly employed R packages in this project include:

```
tidyverse
ggplot2

patchwork  # plot combined placement
ggfortify  # time-series creation
usmap      # plotting lat-long points on US map


# Textual packages for custom theme
ggtext
showtext
purrr
systemfonts
```

## Outputs

Average yearly entries per port are summarized in the following map:

![U.S. map of border entry ports sized by average yearly entries](individual-figures/map.png)

Entries from Canada and entries from Mexico trends over time are summarized here with high and low points marked distinctly:

<p align="center">
  <img src="individual-figures/ca_timescale.png" alt="U.S.-Canada Entries Timeseries" width="48%">
  <img src="individual-figures/mx_timescale.png" alt="U.S.-Mexico Entries Timeseries" width="48%">
</p>

Likewise, state-by-state comparisons of entries from Canada and Mexico are summarized in these boxplots:

<p align="center">
  <img src="individual-figures/ca_pb.png" alt="State Comparisons U.S.-Canada Entries" width="48%">
  <img src="individual-figures/mx_bp.png" alt="State Comparisons U.S.-Mexico Entries" width="48%">
</p>

## Findings
