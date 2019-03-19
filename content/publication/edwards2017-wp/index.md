+++
title = "Testing and recommending methods for fitting size spectra to data"
date = 2017-01-01
authors = ["Andrew M Edwards", "James PW Robinson", "Michael J Plank", "Julia K Baum", "Julia L Blanchard"]
publication_types = ["2"]
selected = "false"
publication = "*Methods Ecol. Evol.*"

url_code = 'https://github.com/andrew-edwards/fitting-size-spectra'

+++

<script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>

<div data-badge-details="right" data-badge-type="medium-donut" data-doi="10.1111/2041-210X.12641" data-hide-no-mentions="true" class="altmetric-embed"></div>

**Abstract**

1. The size spectrum of an ecological community characterizes how a property, such as abundance or biomass, varies with body size. Size spectra are often used as ecosystem indicators of marine systems. They have been fitted to data from various sources, including groundfish trawl surveys, visual surveys of fish in kelp forests and coral reefs, sediment samples of benthic invertebrates and satellite remote sensing of chlorophyll. 

2. Over the past decades, several methods have been used to fit size spectra to data. We document eight such methods, demonstrating their commonalities and differences. Seven methods use linear regression (of which six require binning of data), while the eighth uses maximum likelihood estimation. We test the accuracy of the meth- ods on simulated data. 

3. We demonstrate that estimated size-spectrum slopes are not always comparable between the seven regression- based methods because such methods are not estimating the same parameter. We find that four of the eight tested methods can sometimes give reasonably accurate estimates of the exponent of the individual size distribution (which is related to the slope of the size spectrum). However, sensitivity analyses find that maximum likelihood estimation is the only method that is consistently accurate, and the only one that yields reliable confidence inter- vals for the exponent. 

4. We therefore recommend the use of maximum likelihood estimation when fitting size spectra. To facilitate this, we provide documented R code for fitting and plotting results. This should provide consistency in future studies and improve the quality of any resulting advice to ecosystem managers. In particular, the calculation of reliable confidence intervals will allow proper consideration of uncertainty when making management decisions. 