# Supplementary materials: Fiddler crabs (*Afruca tangeri*) detect second-order motion in both intensity and polarization.
### Supplementary information for: Samuel P. Smithers, Maisie F. Brett, Martin J. How, Nicholas E. Scott-Samuel, and Nicholas W. Roberts. (Communications Biology, 2024) *Fiddler crabs (Afruca tangeri) detect second-order motion in both intensity and polarization.*

## Repository contents
- Raw date from intensity and polarization experiments (.csv files)
- ```Stats and graphs for fiddler crabs see SO motion.r```: R code used to generate the figures for, and perform the statistical analysis on, the data from the intensity and polarization experiments as reported in the manuscript.
- License 

## Statistical analysis & plotting (R)
### Requirements & dependencies
- R version >= 4
- The following packages must be installed:
  - lme4
  - dplyr
  - DHARMa
  - ggplot2
  - cowplot
  - Hmisc
  - Matrix
  - bannerCommenter (optional)

#### Running instructions
1. Download ```Stats and graphs for fiddler crabs see SO motion.r``` from this repository. You will also need to download the "*Data from intensity experiment.csv*" and "*Data from polarization experiment.csv*" data files. Alternatively, you can clone this repository ([instructions for Rstudio here](https://datacarpentry.org/rr-version-control/03-git-in-rstudio/index.html)). 
2. Install any uninstalled dependencies listed above.
3. Open ```Stats and graphs for fiddler crabs see SO motion.r``` and follow instructions within the script.

