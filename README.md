# Comparison of rates of firearm and non-firearm homicide and suicide in black and white non-Hispanic men by US state
### [Corinne A Riddell](corinneriddell.com), [Sam Harper](samharper.org), [Magdalena Cerda](https://www.ucdmc.ucdavis.edu/emergency/ourteam/faculty/cerda.html), and [Jay S Kaufman](jayskaufman.com)

# Project overview

This repository contains the data, code, and R markdown version of a manuscript submitted to *Annals of Internal Medicine* on November 7th, 2017. A second and third revision were submitted on February 15th, and February 25th, 2018. It is unknown whether and how much the difference in excess deaths due to homicide among black men and suicide among white men vary by US state. Such knowledge could inform social policy aimed towards reducing social disparities in health. The objective of this manuscript is to estimate the absolute inequality between non-Hispanic black and white men in firearm and non-firearm homicide and suicide across US states.

# Organization of this Github repository

### Code/ directory

The Code folder contains the two analysis files: Code/1_load-and-clean-data imports the data for analysis and prepares it. Code/2_manuscript-and-figures contains the analytical code, the manuscript text, and the codes to produce the figures.

### Data/ directory

The Data directory has a folder storing the original data (Raw-data/), the cleaned data (Cleaned-data/), and a separate set of data that is cited in the Manuscript's introduction (Cited-data/).

### Plots/ directory

The Plots directory stores the four manuscript figures. 

## How to replicate these analyses

If your intention is to replicate our analysis and you are familiar with Github, please clone this repository. All of the analysis is contained within the files "Code/1_load-and-clean-data" and "Code/2_manuscript-and-figures", and you can run these files within RStudio by running all of the code chunks within these R markdown documents. Remember first to make the cloned repository an RStudio project, so that all of the relative pathways are correct.

If you are unfamiliar with Github, but familiar with R and RStudio, you may wish to download the analysis files by navigating to them and downloading the raw versions and open locally within RStudio. You will also need to download the data files that are referenced in the code chunk `load_CDC_wonder_data` in the first file and `CDC-wonder-intro-data` in the second file. They can be found in the Data/CDC-wonder and Data/Introduction folders, respectively. Please update the pathways to read these data from your local directory where you've saved these files. You can then run the code chunks within RStudio to replicate the analysis. To replicate the paper, you can use the "Knit" button to knit to word or html.

Happy Replicating! Reproducible Research FTW!
