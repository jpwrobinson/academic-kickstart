+++
date = 2016-07-01
title = "Predator-prey mass ratios"
[image]
focal_point = "Center" 
+++

Predator-prey mass ratios (PPMRs) reflect the strength of interactions between predators and prey, and can be used to examine community size structure. PPMRs can be estimated using diet data (e.g. Barnes et al. 2010, Ecology) or with stable isotope methods in which an individual's trophic position is inferred by measuring the fractionation of nitrogen 15-N relative to a baseline value.

Although standard 'additive' approaches assume that 15-N fractionates by 3.4‰, Hussey et al. (2014, Ecol. Lett.) showed that fractionation values are dependent on tissue 15-N and so increase with trophic level.


Figure 1 - trophic position ~ body mass relationship produced using scaled (red) and additive (black) fractionation methods

In a paper led jointly by Dr. Eric Hertz (Simon Fraser University) and myself, we applied Hussey et al.'s (2014) scaled trophic fractionation model to simulated data and North Sea stable isotope data. Our results indicated that the additive stable isotope approach produces incorrect PPMR estimates, and that the extent of the bias is dependent on the baseline 15-N and the trophic level sampled. For those wishing to correctly calculate PPMR from stable isotope data, [here's the code](http://github.com/baumlab/ppmr-isotopes) that applies the Hussey et al. (2014) scaled trophic fractionation model to directly estimate PPMR.

