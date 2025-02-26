# Munition Crater Detection in Synthetic Aperture Radar Imagery Using Deep Learning

A demonstration of high resolution synthetic aperture radar (SAR) imagery segmentation for the detection of munitions-produced craters using a U-Net convolutional neural network (CNN) implemented in PyTorch.

***CONTENTS*

## General Information

This project was initially completed as the capstone for the Masters in Geospatial Intelligence Program at The University of Maryland in Fall of 2023.

Author: Michael Prihoda
Mentor: Dr. Sergi Skakun

Access to high resolution SAR imagery was generously provided by Capella Space through its Data Cooperative Program.

## Background

Modern warfare often results in widespread destruction of infrastructure, facilities, and the landscape in locations where active combat occurs. Significant displacement of population occurs in these areas as many seek safety elsewhere, in hopes of returning once the acute threat of war is no longer present. Many hazards persist in the environment following the cessation of active hostilities and continue to pose a threat to returning populations for generations, particularly unexploded ordnance (UXO). Significant amounts of UXO are the result of artillery shells and similar projectiles failing to detonate, becoming embedded in the soil, and being unearthed later, sometimes with deadly consequences. Explosive munitions from World War I continue to appear each tilling season in parts of Europe, this annual unearthing of war remnants is known as the “Iron Harvest” (Note et al., 2018).

One hundred years after the outbreak of World War I, in 2014 a new conflict began in Europe between Ukraine and the Russian Federation which escalated significantly following Russia’s full-scale invasion in February 2022.  This war between Ukraine and Russia, much like the First World War a century prior, is characterized by the heavy use of artillery: Joseph Stalin’s “god of war” (Hunder, 2023). Between both Ukraine and Russia, 30,000 to 60,000 artillery shells are fired per day (millions per year), in addition to rockets and other explosive projectiles (Levy, 2023). Given the sheer number of shells fired and with each shell facing some probability of failure, a significant number of munitions are emplaced as UXO. Stockpiles of North Korean artillery shells have demonstrated particularly low reliability and high rates of failure with up to one in five shells failing to detonate; Russia hopes to sustain their millions-per-year rate of artillery fire, at least in part, by tapping into these stockpiles (Smith, 2023). As a result of artillery-centric warfare, explosive remnants of war are nearly certain to persist in Ukraine’s environment long-term until it is removed or destroyed.

Removal or destruction of UXO is a time and resource-intensive task, as well as dangerous to those tasked with the work. Fortunately, modern technologies continue to offer ways to locate/detect as well as dispose of UXO with greater efficiency and less risk to explosive ordnance disposal teams and bystanders. Magnetometers, ground penetrating radar, and electromagnetic induction technologies are among those used to precisely identify and locate potentially hazardous UXO. Implementing these technologies effectively first requires knowing where to look. In recent years the deployment of a variety of remote sensing platforms with ever-improving capabilities presents ways to contemporaneously identify areas impacted by artillery and other munitions through the observation of craters which, in turn, reveal areas where UXO is more likely to be present. While current sensors and platforms allow the identification of individual craters by a user, the very high spatial and temporal resolution of remote sensing data makes it unfeasible to manually identify all crater locations along the 1,000km+ line of contact. Prior research demonstrated the applicability of binary segmentation deep learning models on very high-resolution multispectral imagery to automate the identification of munition craters (Duncan et al., 2023). This project and the following pages present a process based on the work of Duncan et al. also for the automated detection of craters but using synthetic aperture radar (SAR) data as the source imagery rather than multispectral/optical data.

## Data

## Methodology

## Results

## Implementation

## References
