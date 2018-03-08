# c14AAR_pres
Abstract for CAA 2018 

## c14bazAAR & oxcAAR -- two R packages for the collection, calibration and modelling of 14C dates

There is hardly any type of data that would be more important for archaeological research and practice than radiocarbon data. This is true for the intrasite level, for regional comparisons and also in cases where processes that have a large spatial and temporal extension are to be investigated. Most comparative studies rely on openly available repositories of published dates -- archives with a long tradition of data collection, processing and maintenance. The number of such archives, with different temporal and spatial foci, has grown enormously in the last two decades. Unfortunately, resulting from this the entire data basis is now highly decentralized and without basic standardisation.

In this paper we would like to introduce two new packages that simplify the handling of radiocarbon data in R. c14bazAAR provides tools to systematically query an ever-expanding selection of 14C data archives and automatically clean and merge the results. oxcAAR serves as an R API to the widely used software package OxCal for calibration and modelling of 14C data. It therefore not only allows for a rational, coherent and reproducible workflow of import, calibration and visualization, it also offers an interface that enables simulation and further statistical analysis within R, which provides the perfect environment for such tasks. Both packages are well interlinked and support tidy data structures, making them compatible with modern and powerful tools like dplyr, sf or ggplot2.

The packages are developed by the ISAAKiel group (Initiative for Statistical Analysis in Archaeology Kiel) https://isaakiel.github.io

**Keywords:** R, Radiocarbon dating, Data collection