---
layout: archive
title: "Visualizations"
permalink: /visualizations/
author_profile: true
redirect_from:
  - /visualizations
header:
  overlay_image: cloud-tail-t_12.png
---

## Phase Evolution of the Cloud-Wind Interactions

The following set of videos illustrate that the motion of fluid elements through phase-space reflect the cloud-wind interaction's evolution.

In each simulation, a spherical, initially motionless, cool cloud is embedded within a hot wind that is 100 times less dense.
The wind moves from left to right and has a Mach number of 1.5.
Each simulation has a resolution of 64 cells per cloud radius.

This first video shows a simulation without radiative cooling.
Mixing rapidly destroys the cloud by homogenizing the gas from the cloud with the gas from the wind.
This destruction is reflected in phase space by the bulk movement of the initially cool and dense gas towards the position of the initially hot and diffuse gas.
{% include video id="504064712" provider="vimeo" %}

This next simulation is similar to the previous one except that inefficient radiative cooling is included.
The cloud's fate is the same as before, except that it takes slightly longer for the cloud to be destroyed.
{% include video id="504064610" provider="vimeo" %}

The following video depicts another simulation of the cloud-wind interaction, but with faster radiative cooling (and the cloud has a different temperature).
In this case, cooling is rapid enough that the cloud not only survives the enconunter, but also shows significant growth.
The phase evolution demonstrates that mixing initially causes mass to be lost from the cool phase.
However, by 4.5 cloud crushing times cooling causes the process to reverse.
{% include video id="504064439" provider="vimeo" %}

This last simulation is similar to the prior one, except that the initial temperature of the cloud is different.
Due to differences in the cooling function, it takes longer for this simulation to start rapidly growing.
{% include video id="503934542" provider="vimeo" %}
