---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a graduate student at the [University of Notre Dame](https://www.nd.edu/) in the [Integrated Biomedical Sciences](https://ibms.nd.edu/) PhD program. I'm a member of the [Whelan Lab](https://whelanlabnd.weebly.com/) in the [Chemistry and Biochemistry Department](https://chemistry.nd.edu/) where we apply analytical chemistry to human health questions, specifically the detection of ovarian cancer. My projects focus on the proteomic characterization of an ovarian cancer biomarker (MUC16), and the optimization of techniques like [capillary electrophoresis](https://en.wikipedia.org/wiki/Capillary_electrophoresis) and [fluorescence anisotropy](https://en.wikipedia.org/wiki/Fluorescence_anisotropy) to characterize [aptamer](https://en.wikipedia.org/wiki/Aptamer) binding to molecular targets. I also enjoy data analysis, using *R*, *python*, and *julia* to streamline data processing and visualization.

Prior to graduate school, I worked as an associate scientist at Pharmaceutical Product Development (PPD) in Biopharmaceutical Method Development & Validation. 

Research
======
## Proteomics of MUC16
MUC16 is a large, heavily glycosylated mucin protein that is a biomarker used to track progression of ovarian cancer. The Whelan lab has made [significant improvements](https://pubs.rsc.org/en/content/articlelanding/2020/an/d0an01701a#!divAbstract) on the peptide coverage of MUC16 utilizing a bottom-up proteomics approach. I am working to identify additional glycosylated peptides that can be used to not only characterize MUC16 expression in cancer patients, but also differential glycosylation. We believe that this will lead to new methods to detect ovarian cancer and ovarian cancer recurrance. 

## Aptamer Characterization
Aptamers are small, functional oligonucleotides that can be used similarly to antibodies in many laboratory and therapeutic applications, with several distinct advantages. One advantage is that they can be developed *in vitro* in a process known as [SELEX](https://en.wikipedia.org/wiki/Systematic_evolution_of_ligands_by_exponential_enrichment). After this SELEX process, it is important to characterize the binding characteristics of an aptamer and its target. I am working on optimizing this process in several ways.
* I recently showed that fluorescence anisotropy (FA) can be used to [efficiently analyze aptamer binding in very low volumes](https://pubs.rsc.org/en/content/articlelanding/2021/AY/D0AY02256J#!divAbstract). I am currently working to apply this knowledge to the automation of FA assays with liquid handling robots. We hope that this will allow for even more efficient characterization and, improve the success rate of SELEX experiments.
* Capillary electrophoresis (CE) is an analytical technique that uses high voltage to separate analytes in a capillary. I am working with home built CE instruments to incorporate FA detection online. Using this technology, we hope to be able to combine mobility shift and FA characterization of aptamer-target binding simultaneously.

Photos and Figures
======
![Home built CE-LIF instrument](/images/)
![R Function to integrate CE-LIF traces](/images/Example_integration.bmp)
![Increased glycopeptide coverage of MUC16](/images/Glyco_vs_non_glyco_peptides_fitz_MUC16_2.jpg)
