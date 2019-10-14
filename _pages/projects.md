---
permalink: /projects/
title: "Projects"
excerpt: "Projects"
author_profile: true
---

## Understanding cortical integration during active sensation

Surround integration in the cortex is thought to be critical for feature extraction and the ultimate generation of perception, however technological limitations have prevented researchers from studying it during brain states in which the animal is actively perceiving its environment. My dissertation research in Hillel Adesnik's lab addresses this by combining in vivo two-photon calcium imaging, layer-specific transgenic mouse lines, and sophisticated whisker stimuli to measure how hundreds of neurons across multiple layers of the primary somatosensory cortex differentially integrate information across surrounding whiskers. In [Pluta & Lyall et al. 2017](https://doi.org/10.1016/j.neuron.2017.04.026) we were able to show that surround integration profoundly shapes the location tuning of cortical neurons but not thalamic neurons, and that this integration is ultimately critical for generating a cortical map of the space scanned by the whiskers. Now we are increasing the dimensionality of our stimulus even further and using sophisticated whisker trimming techniques to get a more complete picture of how neurons in each of the layers performs surround integration.

## Near real-time analysis of calcium imaging data

In partnership with UC Berkeley's Research IT workflow engineer Maurice Manning, we are working on getting an analysis pipeline up and running that moves two-photon calcium imaging data immediately to Berkeley's high performance computing cluster as it's acquired, and then automatically identifies neurons at scale using a state of the art nonnegative matrix factorization approach known as [CaImAn](https://github.com/flatironinstitute/CaImAn). 


## ROIanalysis: a MATLAB toolbox for circling neurons and extracting their activity

Early on in my graduate research, the default calcium imaging analysis pipeline used by many labs was to utilize ImageJ ROI tools that required a lot of clicks, was not streamlined for identifying lots of neurons, and ultimately very inefficient and time consuming. I wrote a toolbox called ROIanalysis that allows users to load in tiff or sbx calcium imaging data, circle and label neurons, and compute their dF/F responses in a painless manner. [This code is available](https://github.com/elyall/ROIselection) on GitHub.

## Intrinsic imaging toolbox in MATLAB

Intrinsic optical signal imaging measures the changes in red light reflectance that accompanies changes in blood oxygenation to localize in the cortex where neurons are processing a sensory stimulus. I have written a GUI, analysis code, and have incorporated [a model of the barrel cortex](https://doi.org/10.1098/rstb.2015.0351) that makes performing intrinsic imaging and mapping the barrel cortex very easy. [This code is available](https://github.com/elyall/IntrinsicImaging) on GitHub.