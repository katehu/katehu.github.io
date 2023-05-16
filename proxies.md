---
layout: page-home
permalink: /proxies/index.html
title: Proxies
---

Intelligent Use of Auxiliary Information

Auxiliary information includes any variables collected but are not the main interest of analysis, e.g., a proxy of an expensive variable of interest, instrumental variables, negative controls. This auxiliary information is often abundant from many data sources, such as remote sensing images, electronic health records, census data, and a baseline survey in a cohort study. Unfortunetly, researchers often ignore this enormous amount of inexpensive but relevant information  in data analysis, missing the opportuntiy to improve the quailty of a study with almost no cost.  My interest is to develop tools to help people harness the full potential of this easy-to-obtain and often free information.

 
Currently,I am developing several methods to leverage auxiliary information to adjust for unmeasured confounding, using techniques in  and proximal causal inference, econometrics, and Bayesian statistics. I focus on recovering the causal estimand for continuous exposure and outcomes, with possibly many weak negative controls. <br/>  

1. [Use negative controls, instrumental variables, and proxies to adjust for unmeasured confounding bias](#bias)
2. [Use proxies in case-cohort studies to enhance inference precision](#precision)
3. [Use auxiliary information to improve study designs](#study-design)



### Use negative controls, instrumental variables, and proxies to adjust for unmeasured confounding bias <a name="bias"></a>


**Jie Hu**, Eric Tchetgen Tchetgen, Francesca Dominici<br/>
“Leveraging Auxiliary Information to Adjust for Unmeasured Confounding in Time Series Study Designs”<br/>
To appear in *Nature Review Method Primer* <br/>
 [[link to slides]](https://github.com/katehu/katehu.github.io/blob/master/Alamo_Symposium_KateHu.pdf)
  

 ### Use proxies in case-cohort studies to enhance inference precision<a name="precision"></a>

   
Software: an R package:<br/>
**Jie Hu** "Fit Additive Hazards Models for Survival Analysis", CRAN - Package *addhazard* (2020). [[link1]](https://github.com/katehu/addhazard) [[link2]](https://cran.r-project.org/web/packages/addhazard/index.html)<br/> 
[[link to A user's manual]](https://cran.r-project.org/web/packages/addhazard/addhazard.pdf)

   
Tutorial1 - analysis of a National Wilms Tumor Study dataset [[link to analysis code](https://www.mn.uio.no/math/english/research/groups/statistics-data-science/handbook-of-case-control-studies/chapter-17/bc_ah_analysis_for_table_17.4.html) <br/>
hosted by *Department of Mathematics, University of Oslo* <br/>

Tutorial2 - analysis of an Atherosclerosis Risk in Communities Study (ARIC) dataset  
[[link to analysis code]](https://static-content.springer.com/esm/art%3A10.1007%2Fs10654-021-00739-3/MediaObjects/10654_2021_739_MOESM1_ESM.pdf) [[link to scientific questions]](https://link.springer.com/article/10.1007/s10654-021-00739-3) <br/>
hosted by *European Journal of Epidemiology*, Jun, 1-14 (2021).<br/>

**Jie Hu**, Norman E. Breslow, Chan Gary, Couper David<br/>
“Estimating Disease Hazard Differences from Case-Cohort Studies” [[link]](https://link.springer.com/article/10.1007/s10654-021-00739-3)<br/>
*European Journal of Epidemiology*, Jun, 1-14 (2021). <br/>
*<small> This article includes methods and software for improving inference precision by leveraging auxiliary variables.<small> <br/> 
   


**Jie Hu** <br/>
"A Z-estimation system for two-phase sampling with applications to additive hazards models and epidemiologic studies" 
   [[link]](https://digital.lib.washington.edu/researchworks/handle/1773/27427) <br/> 
PhD Diss.*University of Washington ResearchWorks Archive* (2014). <br/>
<small> Chapters 4, 5, 6 include methods and results for improving inference and prediction precision in semiparametric models by leveraging auxiliary variables.<small><br/> 

### Use auxiliary information to improve sampling designs<a name="study-design"></a> 

**Hu, J**, Jerkins, J, Goebel, N. Routing Method for Mobile Monitoring Platforms --- A scalable sampling method that dispatches a fleet of vehicles to collect environmental data unbiasedly (U. S. Application Serial No.17/332789) [[link]](https://uspto.report/patent/app/20210377708) <br/>
*<small> This patent proposes an idea to use nearby air quality monitoring stations to determine the sampling time and weights for measuring hyperlocal air quality in each neighborhood with mobile sensing platforms <small> <br/> 

**Hu, J** & Ladoni, M. (2021) Location Selection for Treatment Sampling ---A field Study Design Tool to Optimize Treatment Assignment and Soil Sampling Locations for Model Calibration. (U.S. Patent No. #10,963,606) [[link]](https://uspto.report/patent/grant/10,963,606) <br/> 
*<small> This patent proposes an idea to use auxiliary variables that are correlated with the core study variables in a biogeochemical model to determine sampling locations for evaluating and calibrating the model.<small> <br/> 


