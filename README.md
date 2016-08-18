[![DOI](https://zenodo.org/badge/23770/davismcc/scater_tutorials_open_data.svg)](https://zenodo.org/badge/latestdoi/23770/davismcc/scater_tutorials_open_data)

# `scater` tutorials with open-access data

This repository contains a set of tutorials using the
[scater](http://bioconductor.org/packages/scater/) package to perform
pre-processing, quality control normalisation and visualisation on several publicly available
single-cell RNA-seq data sets.

RMarkdown (.Rmd) files are provided so that you can replicate the
analyses and can be used as templates for analyses of your own
data. HTML (.html) files are provided to show what the RMarkdown files
produce when run, and also show demonstration workflows that could be followed.

Datasets used as examples here include:

* 3000 mouse cortex cells from
[Zeisel et al, 2015](http://science.sciencemag.org/content/347/6226/1138).
* 1200 mouse embryonic cells from [Scialdone et al, 2016](http://www.nature.com/nature/journal/v535/n7611/full/nature18633.html)

More will follow. The analyses shown were carried out on a recent
Macbook Pro laptop, so large computational resources are not required
to analyse datasets of this scale.

Kudos to the authors of these studies who have made their data
available.

* For the mouse cortex data, see the
[Linnarsson Lab website](http://linnarssonlab.org/cortex/).
* For the mouse embryonic cell data, see the
[Cambridge University Stem Cells website](http://gastrulation.stemcells.cam.ac.uk/scialdone2016)


## See for yourself

Check out the results of the `scater` analyses in these HTML reports produced
with R Markdown showing code and results.

* Zeisel et al mouse cortex cells analysis can be seen
  [here](https://rawgit.com/davismcc/scater_tutorials_open_data/master/zeisel_mouse_cortex.html).

* Scialdone et al mouse embyonic cells anlaysis can be seen
[here](https://rawgit.com/davismcc/scater_tutorials_open_data/master/scialdone_mouse_mesoderm.html).


## Do it yourself

Clone this repository to access analyses of open-access single-cell
expression data in R Markdown format so that you can experience the
utility of `scater` and prepare single-cell expression datasets for
your own exploration.

Navigate to your favourite directory and clone:

```
git clone https://github.com/davismcc/scater_tutorials_open_data.git
```

Or you can download the zipped version of the repository from this
page.

To work through the tutorials you will need to have the following
R/Bioconductor packages installed:
* `scater`
* `scran`
* `data.table`
* `cowplot`
* `DT`
* `knitr`

**Install `scater`** from Bioconductor as below, or see the
[scater GitHub page](https://github.com/davismcc/scater) for more
installation instructions. It is recommended also to install `scran`
for additional normalisation and other useful tools for single-cell
data.

```{r}
## try http:// if https:// URLs are not supported
source("https://bioconductor.org/biocLite.R")
biocLite("scater")
biocLite("scran")
```

The rest can be installed with:
```{r}
install.packages(c("data.table", "cowplot", "DT", "knitr"))
```

Further packages may be needed for particular functionality in certain
tutorials/workflows, with guidance provided in them as appropriate.

Enjoy!

---

Davis McCarthy, August 2016 - #researchparasites
