---
title: "Sam Clifford - Research profile"
date: "19 Feb 2018"
output: 
  tufterhandout::html_tufte_handout:
    self_contained: false
    keep_md: true
    css: ["resume.css", "tufterhandout.css"]
    toc: true
    toc_depth: 2
    includes:
      in_header: header.html
bibliography: resume.bib
link-citations: yes
---




# Bio

I'm a statistician working at <a href="http://www.qut.edu.au">Queensland University of Technology</a> on a range of environmental and environmental health problems such as jaguar conservation, reef conservation, and air pollution and its health impacts. In addition, I teach mathematics and statistics to first year science students in the unit [SEB113 - Quantitative Methods in Science](https://www.qut.edu.au/study/unit?unitCode=SEB113).

Much of my work makes use of the following techniques, which one could consider my research interests

* Generalised Additive Models
* Spatial and spatio-temporal statistics
* Bayesian hierarchical linear models
* Exposure-response models



From 2016 I have been employed as a **Postdoctoral Fellow** at the QUT node of the **ARC Centre of Excellence for Mathematical and Statistical Frontiers**, working on a variety of environmental statistics problems such as coral cover in the Great Barrier Reef and jaguar conservation in Peru as well as the dynamics of dengue fever.

<aside>
2016- : <a href="http://acems.org.au/">ARC Centre of Excellence for Mathematical and Statistical Frontiers</a>
</aside>

Between 2013 and 2015 I was employed as a **Postdoctoral Fellow** at the **International Laboratory for Air Quality and Health** (ILAQH) to support the research being done across a variety of topics in air quality. The bulk of my postdoctoral work at ILAQH was related to the UPTECH project. The project seeks to determine the effect of the exposure to airborne nano and ultrafine (UF) particles emitted from motor vehicles on the health of children in schools.

<aside>
2009-2013: PhD -- [International Laboratory for Air Quality and Health](https://www.qut.edu.au/research/our-research/institutes-centres-and-research-groups/international-laboratory-for-air-quality-and-health)

2013-2015: <a href="https://www.qut.edu.au/research/research-projects/uptech">Ultrafine Particles from Traffic Emissions and Children's Health</a>
</aside>


Between 2009 and 2013 I was a **PhD student** at **ILAQH** under the supervision of Professors [Lidia Morawska](http://staff.qut.edu.au/staff/morawska/) and [Kerrie Mengersen](http://staff.qut.edu.au/staff/mengerse/) and Dr [Sama Low Choy](http://staff.qut.edu.au/staff/lowchoy/).

---------------------------------------------------------
Citation                 Description
------------------------ --------------------------------
@phdthesis               _Spatio-temporal modelling of ultrafine particle number concentration_ - Using the Generalised Additive Model to model temporal trends in ultrafine particle number concentration with penalised splines and spatial trends with Gaussian Markov Random fields.

@honours                 Honours thesis on dispersion of a compount in shear-augmented flow 
---------------------------------------------------------

My undergrad was in applied and computational mathematics, focussing on fluid dynamics in my honours year. Over time, I drifted towards Bayesian statistical modelling, where I use semi-parametric regression and hierarchical modelling for spatial, temporal, and spatio-temporal modelling.

<aside>
2004-2008: B AppSc (Hons IIA) -- [QUT Maths](https://www.qut.edu.au/science-engineering/our-schools/school-of-mathematical-sciences) <br>
</aside>

Occasionally, I blog about my research and you can find more about my publication history at QUT ePrints and Google Scholar. Occasionally I publish useful code, including a package for tidying MCMC output from `coda` or `rjags` entitled [`mmcc`](http://mmcc.njtierney.com/), and a package to bring some of the common linear model diagnostics like variance inflation factors and tables of confidence intervals to GAMs from `mgcv` in [`mgcv.helper`](https://github.com/samclifford/mgcv.helper).


<aside>

* <a href="https://github.com/samclifford">GitHub</a>
    * [`mmcc`](http://mmcc.njtierney.com/)
    * [`mgcv.helper`](https://github.com/samclifford/mgcv.helper)
* <a href="http://samclifford.info">Blog</a>
* <a href="https://eprints.qut.edu.au/view/person/Clifford,_Sam.html">QUT ePrints</a>
* <a href="https://scholar.google.com.au/citations?hl=en&user=KbrnxeoAAAAJ&view_op=list_works">Google Scholar</a>
* <a href="http://orcid.org/0000-0002-3774-3882">ORCID</a>
</aside>

A selected list of publications is shown below, indicating recent projects I've been involved with and key papers I've written. A full list of publications is available [here](fullpubs.html).

# Biostatistics for virus dynamics

I am working with colleagues at QUT and <a href="http://www.qimrberghofer.edu.au/diseases/mosquito-borne-viruses/">QIMR</a> to investigate the replication and spread of Dengue fever. The work involves mathematical and statistical modelling of the dynamics of the virus cell, the host and transmission within the population.

<aside>
2017-: <a href="http://www.qimrberghofer.edu.au/diseases/mosquito-borne-viruses/">Dengue fever (QIMR)</a>
</aside>

# Citizen science for spatial statistics

Recent work at ACEMS has focussed on incorporating citizen scientists into traditional spatio-temporal modelling such as species distribution modelling of jaguars and coral cover.

The Monitoring Through Many Eyes project is a collaboration between scientists, data analysts and marine explorers, working together to document, analyse and predict the health of the Great Barrier Reef. The aim is to tap into the power of Citizen Scientists by collating thousands of underwater images take by recreational divers and snorkelers on the Reef each year.

<aside>
2016: <a href="https://www.virtualreef.org.au/">Monitoring Through Many Eyes</a>
</aside>

Through our Many Eyes on the Wild program, we aim to facilitate faster, better decisions about management and monitoring.  We are developing and using these approaches to help conserve jaguars in the Peruvian Amazon.  We are addressing this problem by combining traditional conservation with virtual reality technology, mathematical and statistical modelling, local knowledge and international expertise. 

<aside>
2016: <a href="http://vis.stats.technology/">Many Eyes on the Wild</a>
</aside>


---------------------------------------------------------
Citation                 Description
------------------------ --------------------------------
@reefmain                Spatio-temporal model of coral cover derived from traditional monitoring and citizen science elicitation of captured images

@reefaesthetics          Gathering information from experts and citizen scientists in a virtual environment to understand what people believe makes an aesthetically pleasing reef

@jaguarspatial           Spatial modelling of presence only data with a variety of statistical and machine learning techniques

@bednarz2016virtual      Using virtual environments to elicit information about ecosystems

--------------------------------------------------------



# Urban air pollution and its health effects

Research from my PhD and postdoctoral time with ILAQH has resulted in a number of papers looking at spatio-temporal modelling of urban air pollution with a view to estimating human exposure and modelling its health impact.

---------------------------------------------------------
Citation                 Description
------------------------ --------------------------------
@uptechmain              Main UPTECH paper detailing the inflammatory and pulmonary response to ultrafine particles

@MORAWSKA201775          Indoor sources of exposure in the home, office, school and aged care facilities

@rahman2017nox           Land use regression modelling with variable selection of NO$_\mathrm{x}$ and NO$_2$ concentrations

@rahman2017estimate      Bayesian GAMs used to model urban background particle concentrations and the contribution of new particle formation

@yeganeh2017satellite    Application of statistical and machine learning models used to estimate air pollution concentrations from satellite imagery

@salthammer2016children  Impact of climate and air pollution on children's health at school

@PBDEs                   Multinomial regression modelling to look at the relative proportions of various polybrominated diphenyl ethers across classrooms

@emacpaper               Mathematical and statistical models for particle deposition inside the lung

@mandanantpaper          Analysis of inhaled particles in primary school children

@paper2                  Spatio-temporal model in INLA of air pollution in Brisbane, Australia
---------------------------------------------------------


# Non-parametric modelling of time series data

I am currently working on simulation studies for two papers with a former ACEMS PhD student, Dr Zoé van Havre, where we are looking at finite and infinite mixture modelling methods for classifying action potential data from EEG scans. Early work in my PhD focussed on modelling temporal variation without spatial structure.

---------------------------------------------------------
Citation                 Description
------------------------ --------------------------------
@zoe2017ofmdpm           Overfitted mixtures and Dirichlet process mixtures for spike classification

@bayesiansplineschapter  A book chapter on various implementations of Bayesian spline regression

@finlandpaper            A preprint of an unpublished paper looking into Bayesian GAMs with autocorrelated errors

@Clifford2011            Using GAMs to model temporal trends and covariate effects for PNC in Helsinki, Finland

---------------------------------------------------------

# Atmospheric processes and instrumentation

---------------------------------------------------------
Citation                 Description
------------------------ --------------------------------
@salimi2017nocturnal     New particle formation typically occurs during daylight; here we investigate evidence of night time events

@rivas2017identification Identification of problems with DustTrak performance seen during measurement campaigns -- indicating conditions under which this instrument shouldn't be used

@rohanpm10               Predictive model for whether or not midday new particle formation events will occur based on morning PM$_{10}$ and visibility

@thermodenuder           Semi-parametric regression used to model particle losses in aerosol measuring equipment
---------------------------------------------------------

# Teaching

Since 2013 I have been involved in the development and delivery of *SEB113 - Quantitative Methods for Science* as part of the ST01 Bachelor of Science course at Queensland University of Technology. The course covers a variety of mathematical and statistical topics taught through scientific case studies and makes use of the R language for all computation.

<aside>
2013: Tutor <br>
2013-: Associate Lecturer <br>
2014-: Unit Coordinator
</aside>

In 2015, the teaching team was the recipient of the Vice Chancellor's Performance Award for innovation in redesiging the unit for student success through encouraging engagement with multiple technologies.

---------------------------------------------------------
Citation                 Description
------------------------ --------------------------------
@herdsa2016              Redesign of a first year unit with blended learning to improve student engagement and success
---------------------------------------------------------



# References
