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

## Emergent Turbulence in Cloud-Wind Interactions

The following video illustrates the temperature dependence of the emergent turbulence in a cloud-wind interaction with sufficient cooling for the cloud to be entrained.

In the video, a spherical, initially motionless, cool (T = 5010 K) cloud is embedded within a hot wind that is 1000 times less dense.
The wind moves from left to right and has a Mach number of 1.5.
The simulation has a resolution of 64 cells per cloud radius and the cloud's density was perturbed to break the setup's symmetries.
The video shows slices of density, specific internal energy (which is just temperature divided by mean molecular weight scaled by some physical constants) and turbulent velocity.
{% include video id="764316702" provider="vimeo" %}

The following set of videos compares various properties for collections of runs of a simulation that just differ in resolution.


Each panel in the top row compares measurements taken from each run of the simulation. They look at the first-order velocity structure function, the 1D specific internal energy distribution, and the evolution of the total mass in the cold phase. The velocity structure function was only computed for gas that falls into a particular phase bin (denoted by the shaded region in panel b) that includes the temperature where gas cools most efficiently (denoted by the vertical dotted line in panel b).

Each subsequent rows show data taken from a distinct run of the simulation. In each of these rows, the left panel shows the distribution of velocity differences between adjacent cells (the average of this distribution gives the leftmost value of the corresponding curve in panel a) while the right panel shows the density projection.
Panel a and the panels showing the distribution of the grid-scale velocity differences are all normalized by the maximum sound-speed in the phase bin (the gray regions denote the range of sound-speed values for gas in this phase bin).

This first video shows the same initial conditions as the previous video (density contrast is 1000). It suggests that when turbulence is not resolved (i.e. the grid-scale velocity differences are supersonic) the cold phase undergoes artificial shattering. As we increase resolution (causing the grid-scale turbulence to becomes subsonic), shattering becomes less violent (i.e. the breakup of clouds is less explosive) and the large-scale morphological properties gradually become more converged (the cold phase has a narrower transverse extent).
{% include video id="764330696" provider="vimeo" %}

For comparison, the following video shows a different set of simulations for which the density contrast is 100 and the cloud radius is 56.38 pc.
In this case, turbulence and the large-scale morphological features are better resolved at all resolutions.
{% include video id="764338328" provider="vimeo" %}

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
