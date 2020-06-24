# Analysis-of-Point-In-Time-Count
## Introduction

#### Background
Every year, the Department of Housing and Urban Development (HUD) collects information from Continuum of Cares (CoC) that details the number of homeless people within the United States and within U.S. Territories (DC, Guam, Puerto Rico, Virgin Islands, and Northern Mariana Islands). The CoCs, which act as the lead agency within a region working to end homelessness, will collect this data numerous ways, most commonly by a physical survey count, observation count, or by extrapolation. This process is called the "Point in Time (PIT) Count" and occurs nation wide within the same time period.

Additional details about how the CoC performs this count can be found here: https://www.hudexchange.info/resource/4036/point-in-time-count-methodology-guide/.

#### Data Set 

The original data set, posted as an xlsx file on HUD's website, did not require any modification. This data was uploaded into R by selecting the sheets and range of interest, which comprised of two sheets, each sheet had 9 of 80 columns selected for this report. After the file was read into R, a column was added to the data that assigned the two state abbreviation based off of the CoC code.

## Analysis of Data Set

This analysis will begin by examining the characteristics of the CoCs themselves to gain a rough understanding of how communities are designed. Next, an aggregated analysis of the PIT count results will be examined from a national, state, and community level to observed changes between 2018 and 2019, or to observe the amount of homelessness when compared to different communities/ regions.


## R Markdown
A R Markdown version of this report can be found at: https://rpubs.com/mtalonso/PITCOUNT
