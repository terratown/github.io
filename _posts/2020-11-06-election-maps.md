---
layout: post
title: "Election Maps"
author: "Ane Rahbek Vierø"
categories: stories
tags: [maps, stories, election]
image: electionmap.jpg
---

<em>Map by: [Martín González](https://martingonzalez.net/)</em>

# Election Maps

A classic - and maybe one of the oldest? - type of data visualisation is the art of cartography.
As with all other data visualisations, data visualised on, or as, maps, can be made to tell very different stories, depending on how you visualise it. For spatial data particularly the choice of geographical scale and unit is an important factor for what story is told.  

This is never as clear, as when it comes to the election maps that are used to show how people voted where and which usually are abundant after larger elections.  

While one should be careful labelling any map as 'wrong' or 'correct' (after all a map is always an abstraction and simplification (<em>see for example the old classic ['How to lie with maps'](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjZ_Zyj0MbuAhVF26QKHW1xCeYQFjAIegQIKxAC&url=https%3A%2F%2Fpress.uchicago.edu%2Fucp%2Fbooks%2Fbook%2Fchicago%2FH%2Fbo27400568.html&usg=AOvVaw0gr-X-r9WZTpQvozbspNAw))</em>, specific ways of mapping voting patterns can convey some quite problematic and misleading narratives. Examples are the maps showing voting results per state or geographical extent, resulting in an idea that Trump won a ['landslide victory'](https://www.telegraph.co.uk/news/2016/11/16/that-misleading-breitbart-map-explained-how-trumps-dominance-acr/) in 2016 (hint: the population is not evenly distributed so largest geographical extent ≠ most votes).  

Similarly, using a very large geographical unit reinforces ideas about homogeneous regions where most, if not all, inhabitants vote and think similarly. This is for example the case in many of the maps used to map the results of the national elections in Denmark:

![Map of election results in Denmark, visualised for each municipality](/assets/img/folketingsvalg1.jpg)
<em>Map of election results in Denmark, visualised for each municipality. Source: [dr.dk](https://www.dr.dk/nyheder/politik/valg2015/se-kortet-danmark-delt-i-tre)</em>
<br>
<br>
In contrast, the map below shows the same data and same election results, but does not to the same extent reinforce the idea of clear-cut urban-rural divides in political affiliation.

![Map of election results in Denmark, visualised for each constituency](/assets/img/folketingsvalg2.png)
<em>Map of election results in Denmark, visualised for each constituency. Source: [dr.dk](https://www.dr.dk/nyheder/politik/valg2015/stemmeknuseren-se-hvordan-kredsene-med-flest-rige-singler-og-ledige-stemte)</em>  
  
As described quite elegantly in this [NY-article](https://www.nytimes.com/interactive/2020/10/30/opinion/election-results-maps.html), there are a number of issues with the traditional way we make maps.

For example, showing election results for geographical areas might give some fairly misleading ideas about who got the most votes, since the population density usually varies quite a bit.

One way of getting around this is to use shades based on population density, but it is hard to communicate exactly how to interpret the relationship between color hue and number of votes. Moreover, most people can only distinguish between 5-7 shades of the same color.

![Map of US election results in 2016, using shades to visualize population density](/assets/img/ny_2016.png)
<em>Map of US election results in 2016, using shades to visualize population density. Source: [New York Times](https://www.nytimes.com/interactive/2018/upshot/election-2016-voting-precinct-maps.html?mtrref=undefined&assetType=REGIWALL#3.98/39.52/-97.87)</em>  
<br>
<br>
To overcome this challenge, some turn to so-called cartograms like the one below (in cartograms the size of each unit is sized in proportion with the data visualized on the map).

![A cartogram of the US election results](/assets/img/cartogram.png)
<em>Source: [Worldmapper.org](https://worldmapper.org/us-presidential-election-2020/)</em>

While fun to look at, most people want to be able to locate themselves, or at least their home town in a map, and that is tricky when the map no longer contains the well-known shapes of more common map projections.

The conclusion - maps are difficult to get right! And election maps might be a little bit harder, especially in times of contested results. Below are however a couple of maps which in different ways do a pretty good job at conveying how - and how many - people voted across the country.

![A dasymetric dot density map by Kenneth Field](/assets/img/field_dots.png)
<em>A dasymetric dot density map by [Kenneth Field](https://carto.maps.arcgis.com/apps/webappviewer/index.html?id=8732c91ba7a14d818cd26b776250d2c3) (2016 election).</em>  
<br>
<br>
![Election map based on building footprint and population density](/assets/img/electionmap.jpg)
<em>Election map by [Martín González](https://martingonzalez.net/) visualizing voting distribution based on both building footprint and population density (2020 election).</em>

<img src="/assets/img/field_dots.png" width="40%">.
