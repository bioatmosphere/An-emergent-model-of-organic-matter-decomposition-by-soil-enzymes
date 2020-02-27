# An-emergent-model-of-organic-matter-decomposition-by-soil-enzymes.
**This repository deposits source data and code supporting our model-based analysis of Emergent properties of organic matter decomposition by soil enzymes:**

**Wang, B., & Allison, S. D. (2019). [Emergent properties of organic matter decomposition by soil enzymes](https://doi.org/10.1016/j.soilbio.2019.107522). Soil Biology and Biochemistry, 107522.** 

<!--![GitHub stars](https://img.shields.io/github/stars/bioatmosphere/An_emergent_soil_enzyme_decomposition_model?style=social) -->

![GitHub repo size](https://img.shields.io/github/repo-size/bioatmosphere/An_emergent_soil_enzyme_decomposition_model)
![GitHub contributors](https://img.shields.io/github/contributors/bioatmosphere/An_emergent_soil_enzyme_decomposition_model)
![GitHub forks](https://img.shields.io/github/forks/bioatmosphere/An_emergent_soil_enzyme_decomposition_model?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/bioatmo_sphere?style=social)
![Github All Releases](https://img.shields.io/github/downloads/bioatmosphere/An_emergent_soil_enzyme_decomposition_model/total.svg)

![Emergent Enzyme Kinetics](https://pbs.twimg.com/media/D9zCMN3U8AAq1DF?format=jpg&name=4096x4096)

In detail, this repository stores data & code following the order of figures occurring in our manuscript:

For each figure (seven in total, of which 3 are supporting figures), the source data (.csv) and the corresponding code (.ipynb) doing the statistical analyses (in R/Python) and drawing the figures (in Python 3.6) in Jupyter Notebook are deposited in a seperate folder. More importantly, all 'real' source data, which are literally model outputs, are provided in the /Source Data folder. These source data have the potential to be further tapped into for other analyses.

With JupyterNotebook, step-by-step analyses are demonstrated, facilitating reproducible analyses. Some essential Python packages (Pandas and Numpy, as well as Matplotlib), of course, should be installed before any real re-runs of these notebooks.

Any questions should be directed to B. Wang at wbwenwu@gmail.com or bw8my@virginia.edu

------------------------------------------------------------------------------------------------------------------------------------------
#### File Strucure

**Publication/**

The pulished manuscript in pdf and supporting material in .docx.

**Source Data/**

Data from the model outputs of DEMENT, in contrast to the data presented below which is processed (but just literally data extraction) and derived from these data. How to extract data from these outputs, the code used, is demonstrated in Jupyter Notebooks with R. In addition, parameters setting up the DEMENT is listed.

**Figure_1/**

All data and jupyter notebooks pertaining to the Figure 1

**Figure_2/**

Similarly, all data and jupyter notebooks pertaining to the Figure 2. And the supporting Fig.1 can be derived from here.

**Figure_3/**

Similarly, all data and jupyter notebooks pertaining to the Figure 3

**Figure_4/**

Similarly, all data and jupyter notebooks pertaining to the Figure 4. And the supporting Fig.2 and Fig.3 can be derived from here.
