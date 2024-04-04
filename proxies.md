---
layout: page-home
permalink: /proxies/index.html
title: Proxies
---

# Use Auxiliary Information to Improve Statistical Inference

Auxiliary information includes any variables collected but are not the main interest of analysis, e.g., a proxy of an expensive variable, instrumental variables, and negative controls. This auxiliary information is often abundant from third-party data sources, such as remote sensing images, electronic health records, census data, and a baseline survey in a cohort study. However, researchers often ignore this enormous amount of relevant information, missing the opportunity to improve the quality of a study with almost no cost.  My interest is to develop tools to help interested users harness the full potential of this easy-to-obtain and often free information.

Currently, I am developing methods to leverage auxiliary information to adjust for unmeasured confounding. I focus on continuous exposure and time series data.

## Adjusting for unmeasured confounding bias

**Jie Hu**, Eric Tchetgen Tchetgen, Francesca Dominici<br/>
“Leveraging Auxiliary Information to Adjust for Unmeasured Confounding in Time Series Study Designs”<br/>
 [[Nature Review Method Primer]](https://rdcu.be/dnIzr)  <br/>
 [[Exercise code in slides 11 and 17]](https://github.com/katehu/katehu.github.io/blob/master/Alamo_Symposium_KateHu.pdf)<br/>
 
 **Hu, J.K**., Tchetgen Tchetgen, E.J. <br/>
 ["Causal Inference with Time Series Data and Unmeasured Confounding"](https://sites.google.com/view/ci4ts2023/)<br/>
 *Causal Inference for Time Series Data Workshop @ 39th Conference on Uncertainty in Artificial Intelligence (2023)*

**Hu, J. K**., Zorzetto, D., & Dominici, F.<br/>
"["A Bayesian Nonparametric Method to Adjust for Unmeasured Confounding with Negative Controls"](https://arxiv.org/abs/2309.02631) <br/>
[[Code]](https://github.com/NSAPH-Projects/BNP-For-Unmeasured-Confounding)<br/>
## Enhancing inference precision

for case-cohort studies<br/>

**Jie Hu**, Norman E. Breslow, Chan Gary, Couper David<br/>
[“Estimating Disease Hazard Differences from Case-Cohort Studies”](https://link.springer.com/article/10.1007/s10654-021-00739-3)<br/>
*European Journal of Epidemiology*, Jun, 1-14 (2021). <br/>
<small>This article includes methods and software for improving inference precision by leveraging auxiliary variables.</small>

for case-control studies<br/>
Norman Breslow and **Jie Hu**.<br/> 
["Survival Analysis of Case-Control Data: A Sample Survey Approach"](https://www.taylorfrancis.com/chapters/edit/10.1201/9781315154084-17/survival-analysis-case-control-data-sample-survey-approach-norman-breslow-jie-kate-hu)<br/>
*Handbook of Statistical Methods for Case-Control Studies, Chapman and Hall/CRC*<br/>
<small> Please email me if you don't have access.</small>

for general two-phase sampling studies<br/>
**Jie Hu**<br/>
["A Z-estimation system for two-phase sampling with applications to additive hazards models and epidemiologic studies"](https://digital.lib.washington.edu/researchworks/handle/1773/27427) <br/> 
PhD Diss.*University of Washington ResearchWorks Archive* (2014). <br/>
<small>Chapters 4, 5, 6 include methods and results for improving inference and prediction precision in semiparametric models by leveraging auxiliary variables.</small>
   
#### Software

**Jie Hu**<br/>
["Fit Additive Hazards Models for Survival Analysis"](https://cran.r-project.org/web/packages/addhazard/index.html)<br/>
CRAN - Package *addhazard* (2020)<br/>
[[github]](https://github.com/katehu/addhazard)[[user's manual]](https://cran.r-project.org/web/packages/addhazard/addhazard.pdf)

#### Tutorials

[Analysis of a National Wilms Tumor Study dataset](https://www.mn.uio.no/math/english/research/groups/statistics-data-science/handbook-of-case-control-studies/chapter-17/bc_ah_analysis_for_table_17.4.html)<br/>
hosted by *Department of Mathematics, University of Oslo*<br/>

[Analysis of an Atherosclerosis Risk in Communities Study (ARIC) dataset](https://static-content.springer.com/esm/art%3A10.1007%2Fs10654-021-00739-3/MediaObjects/10654_2021_739_MOESM1_ESM.pdf)<br/>
hosted by *European Journal of Epidemiology*, Jun, 1-14 (2021).<br/>
[[scientific questions]](https://link.springer.com/article/10.1007/s10654-021-00739-3)

## Improving sampling designs
 
**Hu, J**, Jerkins, J, Goebel, N.<br/>
[Routing Method for Mobile Monitoring Platforms --- A scalable sampling method that dispatches a fleet of vehicles to collect environmental data unbiasedly (U. S. Application Serial No.17/332789)](https://uspto.report/patent/app/20210377708) <br/>
<small>This patent proposes an idea to use nearby air quality monitoring stations to determine the sampling time and weights for measuring hyperlocal air quality in each neighborhood with mobile sensing platforms </small>

**Hu, J** & Ladoni, M. (2021)<br/>
[Location Selection for Treatment Sampling ---A field Study Design Tool to Optimize Treatment Assignment and Soil Sampling Locations for Model Calibration. (U.S. Patent No. #10,963,606)](https://uspto.report/patent/grant/10,963,606) <br/> 
<small>This patent proposes an idea to use auxiliary variables that are correlated with the core study variables in a biogeochemical model to determine sampling locations for evaluating and calibrating the model.</small>
