---
layout:     notebook
title:      Mass Spectrometry Stories &#35;1 
author:     David Fischer
tags: 		[Bokeh, Python, Mass Spectrometry, Metabolomics]
subtitle: Improving signal detection in mass spectrometry data
category:  project1

---
### Simulation of LCMS data. Importance of sample number

In the following example you can see an imaginative 2-D plot of mass spectrometry data as a heat map. For the same data, there is a 1-D plot that represents an extracted ion chromatogram.
You can modify parameters like noise level and peak signal strength. Intuitively, peak signal improves when noise is reduced and/or signal strength is increased.
Less intuitively, and the driving motivation for this work is the importance of sample number: If we overlay multiple LCMS samples with similiar signal/noise behaviour together, the observed signal becomes clearer! Try this yourself by modifying the #samples slider.

<iframe src="https://radiant-garden-69872.herokuapp.com/Random_Background_Peak" width="100%" height="1300">
  <p>Your browser does not support iframes.</p>
</iframe>
