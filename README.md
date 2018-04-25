# Comparison of rates of firearm and non-firearm homicide and suicide in black and white non-Hispanic men by US state
### [Corinne A Riddell](corinneriddell.com), [Sam Harper](samharper.org), [Magdalena Cerda](https://www.ucdmc.ucdavis.edu/emergency/ourteam/faculty/cerda.html), and [Jay S Kaufman](jayskaufman.com)

# Project overview

This repository contains the data, code, and R markdown version of a manuscript published by *Annals of Internal Medicine* on April 24, 2018. (Here)[http://annals.org/aim/fullarticle/2679556/comparison-rates-firearm-nonfirearm-homicide-suicide-black-white-non-hispanic] is the free published paper. The paper was first submitted on November 7th, 2017. A second and third revision were submitted on February 15th, and February 25th, 2018. 

The objective of this paper was to compare the rates of firearm and nonfirearm homicide and suicide in black and white non-Hispanic men by U.S. state and to examine whether these deaths are associated with state prevalence of gun ownership.

# Organization of this Github repository

### Code/ directory

The Code folder contains the two analysis files: Code/1_load-and-clean-data imports the data for analysis and prepares it. Code/2_manuscript-and-figures contains the analytical code, the manuscript text, and the codes to produce the figures. It also contains a supplementary appendix file that contains "table versions" of Figures 1 and 2 that are shown in the Plots/ directory. This file is Code/3_supplementary-appendix. The .Rmd version shows the code and the .md version contains the rendered tables that are formatted for online viewing.

### Data/ directory

The Data directory has a folder storing the original data (Raw-data/), the cleaned data (Cleaned-data/), and a separate set of data that is cited in the Manuscript's introduction (Cited-data/).

### Plots/ directory

The Plots directory stores the four manuscript figures. 

## How to replicate these analyses

If your intention is to replicate our analysis and you are familiar with Github, please clone this repository. All of the analysis is contained within the files "Code/1_load-and-clean-data" and "Code/2_manuscript-and-figures", and you can run these files within RStudio by running all of the code chunks within these R markdown documents. Remember first to make the cloned repository an RStudio project, so that all of the relative pathways are correct.

If you are unfamiliar with Github, but familiar with R and RStudio, you may wish to download the analysis files by navigating to them and downloading the raw versions and open locally within RStudio. You will also need to download the data files that are referenced in the code chunk `load_CDC_wonder_data` in the first file and `CDC-wonder-intro-data` in the second file. They can be found in the Data/CDC-wonder and Data/Introduction folders, respectively. Please update the pathways to read these data from your local directory where you've saved these files. You can then run the code chunks within RStudio to replicate the analysis. To replicate the paper, you can use the "Knit" button to knit to word or html.

Happy Replicating! Reproducible Research FTW!
