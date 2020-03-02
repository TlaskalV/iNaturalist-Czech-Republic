# iNaturalist stats for Czech Republic Feb 2020
Spatiotemporal focused statistics based on research grade observations for Czech Republic accessed on February 2020.

<div float="right">
    <img align="right" src="/iNaturalist_logo.png?raw=true" width="100px"</img>
</div>

## Parts

* [Intro](#introduction)
* [Time aspect](#time-aspect)
* [Density of obs](#density-of-obs)
* [Observation increase](#observation-increase)
* [Seasonal differences](#seasonal-differences)
* [Observed organisms](#observed-organisms)
* [More IDs needed](#more-IDs-needed)
* [References](#references)

## Introduction
Intentionally avoiding user-focused statistics here are some data about iNaturalist observations from Czech Republic downloaded before main observation season of 2020. There were **two City nature challenge** campaigns in Prague which boosted obs upload. 

From the 85 726 verifiable obs (28th Feb 2020) there are **52 022 (60.7%) which made it to research grade** and have GPS coordinates available. City challenge 2019 weekend (April) represented top three days (total 4 471 obs, 8.6%) in the Czech observation history.

Are you coming to this page later in 2020 and do you wonder what is new among observations? Check [iNat page here](https://www.inaturalist.org/observations?place_id=8264)


---

**TLDR** Hotspots of observations are in a big cities and protected areas. 

City Challenge considerably increased number of observations but these are mostly plants and birds. 

Early spring and late autumn observations are underrepresented.

Insects, fungi and spiders have potential for increase in the database of research grade obs. More specialists are needed.


---

## Time aspect
Below is statistics about speed of data upload and verification. Displayed are **means from obs since 2018** which represented increase in iNat usage in Czech Republic (n = 34 269, 65.9% from research grade).

| status | nickname |  days |
|:---------:|:-------:|:-------:|
|    time needed to post obs     | observer efficiency |  13.8 ± 0.3     | 
|  time needed for reaserach grade   |  community efficiency | 41.6 ± 0.5    |
|    since obs to research grade     | whole observation time life |  55.4 ± 0.6    |


## Density of obs
Shows observation density for the whole country. Interestingly, density hotspots are not restricted to bigger cities with a lot of users but are also present in protected areas. This is visible especially in the smaller areas such as Palava and Podyji. Further hotspots are due to locally active users (Ceska Lipa, Novy Jicin). 

Places with less or no observations are often less visited, not so accessible locations (Beskydy, Jeseniky, Zelezne hory, Cesky Les).

<div align="center">
    <img src="/hex_map_edited.png?raw=true" width="1000px"</img> 
</div>


Historical insight. Some observations come from from the users' picture archives. 

<div align="center">
    <img src="/hex_map_history_edited.png?raw=true" width="1000px"</img> 
</div>


## Observation increase

Histrogram of observations since 2018.

<div align="center">
    <img src="/plot_obs.png?raw=true" width="600px"</img> 
</div>

Same data as **cumulative sum** with fitted prediction model. Plato phase starting in autumn  in winter 2019 after City challenge boost is well visible.

<div align="center">
    <img src="/plot_obs_cum_sum.png?raw=true" width="600px"</img> 
</div>

## Seasonal patterns

Total observation sum per month. Main season is from April to June. starting with July the observation number is decreasing towards low values in winter.

<div align="center">
    <img src="/plot_season.png?raw=true" width="600px"</img> 
</div>

## Observed organisms

Organisms recorded in the iNat database are grouped into iconic names similarly to the webpage. Upper chart has log-transformed y axis to better display differences in low abundant taxons. Interestingly, mammals are not among top observed groups. Plants are easy to observe they do not run ;) Aves can fly away but their occurrence in the cities is high and are observed often.

<div align="right">
    <img src="/icons.png?raw=true" width="200px"</img> 
</div>

<div align="center">
    <img src="/plot_kingdom.png?raw=true" width="600px"</img> 
</div>

Let's look at the **seasonal patterns of the top four observed taxon**. Plants and birds are enriched by City challenge. Insects and fungi are not influenced by campaigns and have expectable pattern corresponding to their occurrence throughout the year.

<div align="center">
    <img src="/plot_dominant_kingdoms.png?raw=true" width="600px"</img> 
</div>

## More IDs needed

From the 85 726 verifiable obs (28th Feb 2020) there are **25 494 (29.7%) obs without community ID (no research grade)**. 

Who are these? Do we need more specialists on these taxa?

<div align="center">
    <img src="/plot_kingdom_need_id.png?raw=true" width="600px"</img> 
</div>

## References

This analysis would not be possible without following awesome packages.

-   base (R Core Team 2019a)
-   forecast (Hyndman et al. 2020)
-	ggthemr (Tobin 2020)
-	lubridate (Grolemund and Wickham 2011)
-   OpenStreetMap (Fellows and JMapViewer library by Jan Peter Stotz)
-	patchwork (Pedersen 2017)
-   rgdal (Bivand, Keitt, and Rowlingson 2019)
-   Rmisc (Hope 2013)
-   tidyverse (Wickham 2017)

