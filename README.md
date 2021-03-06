# SLIP

We developed an R package for change-point testing with FDR control in large-scale data streams.

Please refer to our paper: *Activation Discovery with FDR Control: Application to fMRI Data* by Mengtao Wen, Guanghui Wang, Changliang Zou, and Zhaojun Wang.

## Installation
Before installing this package, the dependence packages "glmnet", "POET", "CovTools", "simex", "knitr", and "rmarkdown" need installation, which can be fulfilled by the R command:

    install.packages(c("glmnet", "POET", "CovTools", "simex", "knitr", "rmarkdown"))

Then the package can be installed by the R command:
  
    devtools::install_github("MengtaoWen/SLIP", build_vignettes = TRUE)

The vignette introducing the usage of the **SLIP**, can be browsed by the R command:
	
    browseVignettes("SLIP")
