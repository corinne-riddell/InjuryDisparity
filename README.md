# Comparison of rates of firearm-related and firearm-unrelated homicide and suicide in black and white non-Hispanic men by US state
### [Corinne A Riddell](corinneriddell.com), [Sam Harper](samharper.org), [Magdalena Cerda](https://www.ucdmc.ucdavis.edu/emergency/ourteam/faculty/cerda.html), and [Jay S Kaufman](jayskaufman.com)

This repository contains the data, code, and R markdown version of a manuscript submitted to *Annals of Internal Medicine* on November 7th, 2017. 

To view the R markdown version of this letter, please navigate to [InjuryDisparity/Inequality_manuscript.md](https://github.com/corinne-riddell/InjuryDisparity/blob/master/Code/Inequality_manuscript.md).

### Overview

It is unknown whether and how much the difference in excess deaths due to homicide among black men and suicide among white men vary by US state. Such knowledge could inform social policy aimed towards reducing social disparities in health. The objective of this manuscript is to estimate the absolute inequality between non-Hispanic black and white men in firearm- and non-firearm-related homicide and suicide across US states.

### How to replicate these analyses

If your intention is to replicate our analysis and you are familiar with Github, please clone this repository. All of the analysis is contained within the file Inequality_manuscript.Rmd, and you can run this file within RStudio by running all of the code chunks within this R markdown document. Remember first to make the cloned repository an RStudio project, so that all of the relative pathways are correct.

If you are unfamiliar with github, but familiar with R and RStudio, you may wish to download the analysis file by navigating to Inequality_manuscript.Rmd. You can download the raw version of this file and open locally within RStudio. You will also need to download eight data files that are referenced between lines 78 and 93 of the Rmd file. They can be found in the Data/Men folder. Please update the pathways to read these data from your local directory where you've saved these files. You can then run the code chunks within RStudio to replicate the analysis. To replicate the paper, you can use the "Knit" button to knit to word or html.

Happy Replicating! Reproducible Research FTW!
