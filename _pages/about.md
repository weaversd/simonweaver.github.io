---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a graduate student at the [University of Notre Dame](https://www.nd.edu/) in the [Integrated Biomedical Sciences](https://ibms.nd.edu/) PhD program. I'm a member of two labs in the [Chemistry and Biochemistry Department](https://chemistry.nd.edu/): the [Champion Lab](https://championlab.weebly.com/) and the [Whelan Lab](https://whelanlabnd.weebly.com/). I am also a [CBBI Fellow](https://cbbi.nd.edu/), an NIH funded program to encourage collaboration at the interface of biology and chemistry. My projects focus on method development in bottom-up proteomics, both in sample preparation as well as data analysis and informatics. I use capillary electrophoresis, liquid chromatographay, and mass spectrometry in the lab, and I develop accessible informatics tools using *R* and *python* for the analysis of resulting proteomics data.

Prior to graduate school, I worked as an associate scientist at Pharmaceutical Product Development (PPD) in Biopharmaceutical Method Development & Validation. 

Research
======
## Champion Lab - Small protein detection and characterization
Small proteins (S-prots) are an understudied area of the proteome, and are often missed in normal proteomic workflows due to loss in sample preparation as well the lack of genetic information which is required for database searching. I am developing tools to identify these proteins using Ribo-seq data and Data Independent Acquisition (DIA) along with informatics tools to analyze the resulting spectra. Additionally, I have developed a tool called [PrIntMap-R](https://championlab.shinyapps.io/printmap-r/) which is a web app that has a suite of tools avalible for protein coverage visualization and comparison of shotgun proteomics datasets.

## Whelan Lab - Ovarian cancer biomarker characterization
MUC16 is a large, heavily glycosylated mucin protein that is a biomarker used to track progression of ovarian cancer. The Whelan lab has made [significant improvements](https://pubs.rsc.org/en/content/articlelanding/2020/an/d0an01701a#!divAbstract) on the peptide coverage of MUC16 utilizing a bottom-up proteomics approach. I am working to identify additional glycosylated peptides that can be used to not only characterize MUC16 expression in cancer patients, but also differential glycosylation. We believe that this will lead to new methods to detect ovarian cancer and ovarian cancer recurrance. I recently [published a paper](https://pubs.rsc.org/en/content/articlelanding/2022/ay/d1ay02145a/unauth) detailing how I have used preparative capillary electrophoresis (CE) to improve the proteomic coverage of MUC16, and how the technique may be applied to the characterization and detection of biomarkers.

Photos and Figures
======
![MUC16_peps](/images/CCM_C_MUC16_coverage_notitle.png)
Increased MUC16 peptide coverage using CE Fractionation. Identified peptides shown with vertical colored lines.

------

![PrIntMap-R](/images/P01009.png "this is the title")
Intensity vs Amino Acid position for protein P01009 for a control sample and a enzymatically deglycosylated sample. Potential N-glyco sites highlighted in purple. Export from [PrIntMap-R](https://championlab.shinyapps.io/printmap-r/)

------

![Example_integration](/images/Example_integration.bmp)
R Script to plot and integrate the raw data collected by the Avalanch Photodiode (APD) detector from the home built CE-LIF system.

------

