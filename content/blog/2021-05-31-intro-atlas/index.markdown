---
title: Snow Algae Atlas Project Overview
author: Casey Engstrom
date: '2021-05-31'
slug: intro-atlas
categories: []
tags: [snow algae, community science, citizen science, volunteer, watermelon snow, satellite, ground validation, Quarmby Lab, Simon Fraser University, British Columbia]
subtitle: ''
summary: 'What are snow algae and why should we care? Introduction to Snow Algae Atlas satellite classification, and how community science can help.'
description: 'Snow algae atlas project overview and motivation, introduction to community citizen science project to map snow algae and ground validate satellite imagery'
authors: []
lastmod: '2021-05-31T16:58:32-07:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---


Although we typically think of snow as sterile and lifeless, in summer the snow surface is in fact teeming with life. The melting snow provides liquid water that supports pink blooms of single-celled algae called 'watermelon snow', which feed a diverse [microbiome](https://blog.alpineclubofcanada.ca/state-of-the-mountains/2020/4/14/watermelon-snow-a-microscopic-serengeti) of microscopic grazers, parasitic fungi, and symbiotic bacteria. Fascinating in its own right, this microbiome is also important for its role in the broader ecosystem: the algae "eat away" at the snow. The red algae darken the snow surface, melting away pockets of snow like holes in Swiss cheese. 

![albedo-effect](albedo_effect.jpg)

By regulating snow melt, snow algae could play a vital role in mountain ecosystems. The timing and release of snowmelt impacts plant phenology in alpine meadows, and provides water throughout the summer for downstream habitats. Among other things glacial runoff cools the water temperature for salmon, and transports nutrients that fertilize oceanic plankton. Summer snow reservoirs are also an important source of water for human irrigation and drinking water, and early snow meltout can tip the scales towards drought and wildfire. Snow is an excellent reflective surface, so loss of snow cover means more solar energy absorbed by Earth---another vicious feedback loop of global warming.

We still don't know how widespread or frequent these blooms are, or whether they are increasing with climate change. Here in British Columbia, we see entire glaciers almost completely covered in pink snow. The pink snow tends to occur at middle elevations in the 'Goldilocks zone': too low and there is no snow in summer, too high and the snow remains frozen and the algae can't grow. So looking for pink snow in satellite images seems like a good place to start. 


![Satellite image of pink snow on the Vowell Glacier, Bugaboos, 2020](s2-vowell.png)

However, other things also cause the snow to appear pink in satellite images: for example mineral dirt, or ash from wildfires. To differentiate real algae from false positives like ash and dust, we used a classification algorithm (called Random Forest) that predicts whether it is algae or something else. The algorithm was trained by visual interpretation of satellite images--admittedly subjective. But, now we can make predictions. And go out in the field and test those predictions.


![Pink Snow on the Vowell Glacier, Bugaboos, 2020](vowell.png)


This summer, hikers and mountaineers can help us ground validate our snow algae satellite map by visiting predicted "Algae" and "Other" locations. Here's how it works: a few days before your trip, check the [web app](https://caseyengstrom.users.earthengine.app/view/snow-algae-ground-truth) for any predicted points in your region. In the field, navigate to those points with the Gaia GPS app and classify whether or not the point is predicted correctly.

![catamount](cat4.jpg)

If you like to spend time in the mountains, please consider [signing up](https://form.jotform.com/211535914885059) to participate in our citizen science project. As a bonus, participants recieve a free 1-year Gaia GPS Premium membership on signup! For more information, please see the [step-by-step instructions](https://caseyengstrom.ca/blog/volunteer-protocol/). 

**2022 UPDATE: This project is no longer actively recruiting volunteers.** If you are still interested in volunteering, please see [https://wp.wwu.edu/livingsnowproject/](https://wp.wwu.edu/livingsnowproject/).
