# iNaturalist stats for Czech Republic Dec 2020
Summary of iNaturalist research grade observations for Czech Republic accessed on December 2020 through GBIF database [DOI](https://doi.org/10.15468/dl.afye4c)

<div float="right">
    <img align="right" src="/iNaturalist_logo.png?raw=true" width="100px"</img>
</div>

[![DOI](https://zenodo.org/badge/244349094.svg)](https://zenodo.org/badge/latestdoi/244349094)

## Parts

* [Intro](#introduction)
* [Density of obs](#density-of-obs)
* [Observation increase](#observation-increase)
* [Diversity increase](#diversity-increase)
* [Seasonal differences](#seasonal-differences)
* [Weekday differences](#weekday-differences)
* [Observed organisms](#observed-organisms)
* [Diversity within taxons](#diversity-within-taxons)
* [Contribution of main observers](#contribution-of-observers)
* [References](#references)

## Introduction
Data about iNaturalist observations from Czech Republic downloaded at the end of busy year 2020 through GBIF database. There were **three City nature challenge** campaigns in Prague and Brno which boosted obs upload. 

There are **87 021 observations which made it to research grade** and have GPS coordinates available. This represent 0.4% of global iNaturalist research grade observations. City challenge 2020 weekend (April) represented top four days (total 5 478 obs) in the Czech observation history (6.3%).

In total there are **4 850 different observed species**. 29.8% of them are observed only once (i.e. singletons).

Are you coming to this page later in 2021 and do you wonder what is new among observations? Check 
* [iNat page here](https://www.inaturalist.org/observations?place_id=8264) 

or 

* [GBIF webpage for iNaturalist](https://www.gbif.org/dataset/50c9509d-22c7-4a22-a47d-8c48425ef4a7). 

This GitHub repo is based on [GBIF download](https://doi.org/10.15468/dl.afye4c).


---

**TLDR** 

* Hotspots of observations are in a big cities and protected areas. 

* City Challenge considerably increased number of observations but these are mostly plants and birds. 

* Early spring and late autumn observations are underrepresented.

* almost 30% of observations are taxonomic singletons



---


## Density of obs
Shows observation density for the whole country. Interestingly, density hotspots are not restricted to bigger cities with a lot of users but are also present in protected areas. This is visible especially in the smaller areas such as Palava and Podyji. Further hotspots are due to locally active users (Ceska Lipa, Novy Jicin, Kromeriz). 

Places with less or no observations are often less visited, not so accessible locations (Beskydy, Jeseniky, Zelezne hory, Cesky Les).

<div align="center">
    <img src="/dot_map.png?raw=true" width="1000px"</img> 
</div>


Historical insight. Some observations come from the users' picture archives. 

<div align="center">
    <img src="/hex_map_history_edited.png?raw=true" width="1000px"</img> 
</div>


## Observation increase

Per day observation count since 2018.

<div align="center">
    <img src="/plot_obs.png?raw=true" width="600px"</img> 
</div>

Same data plotted as **cumulative sum**. 

<div align="center">
    <img src="/plot_obs_cum_sum.png?raw=true" width="600px"</img> 
</div>

## Diversity increase

Diversity increase as per day count of species observed for the first time in Czech Republic.

<div align="center">
    <img src="/plot_div_increase.png?raw=true" width="600px"</img> 
</div>

## Seasonal patterns

Total observation sum per month. Main season is from April to July. starting with August the observation number is decreasing towards low values in winter.

<div align="center">
    <img src="/plot_season.png?raw=true" width="600px"</img> 
</div>

## Weekday patterns

Saturday is the best day for observations! Go out and maybe you will meet other observers. Mean values are calculated based on records since 2018.

<div align="center">
    <img src="/plot_weekday.png?raw=true" width="600px"</img> 
</div>

## Observed organisms at the phylum level

Interestingly, mammals are not among top observed groups. Plants are easy to observe they do not run ;) Aves can fly away but their occurrence in the cities is high and are observed often. Note low count of Other phyla.

<div align="center">
    <img src="/plot_kingdom.png?raw=true" width="600px"</img> 
</div>

Let's look at the **seasonal patterns of the top six observed phyla**. Plants and birds are enriched by City challenge. Insects and fungi are not influenced by campaigns and have expectable pattern corresponding to their occurrence throughout the year.

<div align="center">
    <img src="/plot_dominant_kingdoms.png?raw=true" width="600px"</img> 
</div>

## Diversity within taxons
Diversity within phyla shows Insecta to be more diverse with much less observation than Plantae. It is easy to observe vast diversity of Insecta. Similarly for fungi.

<div align="center">
    <img src="/diversity_per_taxon.png?raw=true" width="600px"</img> 
</div>

## Contribution of main observers
Observation count versus species count for main observers. Some of them repeat observed species, some of them upload new species quite often. The green line indicates 1:1 (observation:new species).

<div align="center">
    <img src="/user_contribution.png?raw=true" width="600px"</img> 
</div>


## References

This analysis would not be possible without following awesome packages.

-   base (R Core Team 2019a)
-	ggthemr (Tobin 2020)
-	ggrepel (Slowikowski 2019)
-	lubridate (Grolemund and Wickham 2011)
-   OpenStreetMap (Fellows and JMapViewer library by Jan Peter Stotz)
-   tidyverse (Wickham 2017)

