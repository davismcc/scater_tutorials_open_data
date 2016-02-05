# `scater` tutorials with open-access data

A set of tutorials using the [scater]() package to QC publicly available
single-cell expression data sets

## See what it looks like

Check out the results of the analyses in these HTML reports produced
with R Markdown showing code and results.

* Analysis of
  [Zeisel et al, 2015](http://science.sciencemag.org/content/347/6226/1138)
  data with `scater` can be seen
  [here](https://rawgit.com/davismcc/scater_tutorials_open_data/master/zeisel_mouse_cortex.html). Kudos
  to the authors of that study who
  have made their data available at the
  [Linnarsson Lab website](http://linnarssonlab.org/blobs/cortex/).
* More to follow...


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
* `data.table`
* `cowplot`
* `DT`
* `knitr`

See the [scater GitHub page](https://github.com/davismcc/scater) for
installation instructions for that package. The rest can be installed
with:
```{r}
install.packages(c("data.table", "cowplot", "DT", "knitr"))
```

Enjoy!

---

Davis McCarthy, February 2016 - #researchparasites
