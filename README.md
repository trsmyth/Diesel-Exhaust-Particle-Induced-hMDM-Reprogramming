# Diesel-Exhaust-Particle-Induced-hMDM-Reprogramming

This repository contains scripts associated with the February 2024 APSselect article "Diesel exhaust particles induce polarization state-dependent functional and transcriptional changes in human monocyte-derived macrophages" published by the American Journal of Physiology-Lung Cellular and Molecular Physiology, available at: https://doi.org/10.1152/ajplung.00085.2023.

Author: Timothy Smyth

These scripts are presented in separate folders corresponding to specific analyses. The following descriptions are based on the order of appearance in the article.

Meso Scale Discovery: 
- Results from the Meso Scale V-PLEX Human Cytokine 30-Plex are analyzed and visualized using principal component analysis (PCA), heatmaps, and 2-way repeated measures (RM) ANOVA with Fisher LSD followed by graphing.

Fluidigm:
- Results from the 48 gene Fluidigm panel are analyzed and visualized using principal component analysis (PCA), heatmaps, and 2-way repeated measures (RM) ANOVA with Fisher LSD followed by graphing.

Seahorse XF
- Results from Seahorse XF modified mito stress tests are analyzed and visualized using 2-way repeated measures (RM) ANOVA with Fisher LSD followed by graphing.

In addition, an improved graphing method is presented. 

Improved Graphing Method:
- Graphing methods employed in the manuscript add statistical results directly to the plots using the ggpubr function stat_pvalue_manual. This causes the y axis to elongate to accommodate these results which can dimminish the appearance of the bar graphs and their relative levels compared to other groups. This method generates a seperate graph with statistics bars/values and merges the two plots together using the patchwork function wrap_plots.
