# PhD projects.


##### This page will contain my Ph.D. projects as a data analyst.

## Higgs to Four Leptons with CMS Open Data
This is my first project during my Ph.D. where I reproduced the Higgs to four leptons analysis with CMS Open Data. The datasets used for this validation analysis are only partially overlapping with the one used in the Higgs discovery paper [[link]](https://www.arxiv.org/abs/1207.7235). This validation analysis aims to give an example of using CMS Open Data for educational applications and show the potential of its usage for research applications. The analysis is presented in four different levels of difficulties. More details about this project including the example code is publicly released in this [[link]](https://opendata.cern.ch/record/5500). The example is also adapted for GitHub, kindly provided by Freya Blekman [[link]](https://github.com/cms-opendata-analyses/HiggsExample20112012). I also gave a presentation at DPG 2018 where the slides are publicly accessible [[link]](https://cms.desy.de/sites/sites_desygroups/sites_extern/site_cms/content/e78437/e83421/e85075/e142142/e89447/e120786/DPG2.pdf).

 Many people have benefited from this example on the usage of CMS Open Data[[link1]](https://www.nature.com/articles/s41567-018-0342-2) [[link2]](https://www.epj-conferences.org/articles/epjconf/abs/2021/05/epjconf_chep2021_01004/epjconf_chep2021_01004.html). Even now, I am contacted by students who use my example as reference for their projects. I am really happy to answer those questions, hoping that it is useful and they learn something from it. 

 Since I have used CMS Open Data for many projects, I would like to talk a bit more about it below. 

### CMS Open Data
CMS Open Data [[link]](https://opendata.cern.ch/docs/about-cms) are original data used by CMS members that are released to the public via the CERN Open Data portal [[link]](https://opendata.cern.ch/docs/about). CMS Open Data can not only be used for research but also for educational purposes. 

Educational applications usually target school pupils and university students to provide knowledge about high energy physics in a fun and educational way without any prior knowledge. Research applications focus on people who want to conduct and publish their analysis using the original preserved data. To achieve both purposes, several example codes of different analyses are available in the portal for users to analyze. 

Figure below shows the official CMS plot for the "Higgs to four leptons" channel, shown on the day of the Higgs discovery announcement (left) and a similar plot using CMS Open Data (right). Picture taken from [[here]](https://home.cern/news/news/experiments/cms-releases-more-one-petabyte-open-data).
![Higgs](/Higgsleptons.png)

 ------------------------

## Measurement of Total and Differential Charm Cross Sections at 7 TeV with the CMS Detector
This is my main Ph.D. project :)

The project presents the total charm cross section measurement in the full kinematic phase space of pp collisions at the LHC. It was performed using open data (2010) from the CMS experiment at a center-of-mass energy of 7 TeV due to its special low transverse momentum (p<sub>T</sub>) tracking. This is the first and so far only measurement of charm 7 TeV in CMS.

### Motivation of This Work
Humanity is full of curiosity to acquire knowledge. This knowledge includes the question what are the smallest particles in the world that make up matter. Particle physics is one of the physics fields that allow the study of matter at its fundamental level. The theory that describes the elemntary particles and their interaction is referred to as the Standard Model. Exploring the particles within the Standard Model is interesting because there are still many aspects that are not fully understood. In addition, experimental measurements are important as they may reveal deviations that point to physics beyond the Standard Model.

![SM](/higgstan_sm.png)

Figure above shows the Standard Model of particle physics. The cute picture was taken from [[link_needtoupdate].](https://higgstan.com/particle-image/)

In this work, a study on a particle called charm quark is conducted. The interaction of charm quarks, like any other quarks, is mainly governed by a part of the Standard Model called Quantum Chromodynamics (QCD). The measurement of charm production thus provides a way to test QCD predictions. These can then be used to further constrain the charm quark mass, the proton parton density functions, and other QCD parameters.

![phase-space](/phase_graphnew.png)

Figure above shows the phase space in transverse momentum vs rapidity in which different LHC experiments performed their measurements of charm quark production so far [[needtoupdate]](needtoupdate). As in the present analysis, these analyses measured D mesons or other charm hadrons. Some of these measurements were extrapolated to the full kinematic phase space with a large extrapolation factor in order to extract the total charm cross section. The corresponding total cross section values are thus strongly theory/model dependent. This analysis aims to cover the largest possible fraction of the total phase space in order to extract the total charm cross section with the smallest possible extrapolation, and thus smaller theoretical uncertainty. 

<span class="normal">
The charm reconstruction was done through the D<sup>&lowast;&plusmn;</sup> &rarr; K<sup>&mnplus;</sup>&#8508;<sup>&plusmn;</sup>&#8508;<sup>&plusmn;</sup> final state. Since this analysis is statistically limited, one of the main strategies of this analysis is to use pileup vertices from muon and electron datasets as a physics resource. This analysis has covered the largest possible kinematic phase space at the LHC from a single experiment with p<sub>T</sub> down to 1 GeV. This includes three new phase space regions where no D<sup>*</sup> cross section measurement has been done before at the LHC for p<sub>T</sub> below 3.5 GeV. The total charm cross section is then extracted from this analysis. By combining with the LHCb measurements, which covered most of the region outside the CMS detector coverage, and some extrapolations from Monte Carlo Pythia and FONLL, the total charm cross section for the full kinematic phase space is measured to be 9.40 &plusmn; 0.45 (statistical) with uncertainty of &plus;2.5 and &minus;0.95 (FONLL/Pythia) mb with an extrapolation factor of 1.4 throughout all phase space.
This is the smallest extrapolation achieved for the total charm cross section at the LHC so far.
</span>