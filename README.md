# Sydney xaringan

University of Sydney theme for xaringan (remark.js)

Example and guide here: http://garthtarr.github.io/sydney_xaringan

To get started you will likely need:

```r
install.packages('xaringan')
remotes::install_github("mitchelloharawild/icons")
install.packages("RefManageR")
install.packages("DT")
install.packages("tidyverse")
install.packages("googleVis")
```

To run the example, you may also need to follow the instructions [here](https://github.com/mitchelloharawild/icons) to download the set of fontawesome icons as part of the **icons** package setup, i.e. if you haven't already, you'll need to run

```r
icons::download_fontawesome()
```

For further customisation you might consider the [xaringanExtra](https://github.com/gadenbuie/xaringanExtra) package.

Other notes
## Convert to other file formats

install.packages("remotes")
install.packages("pdftools")

# load the library
library(xaringanBuilder)
# load the library
library(pdftools)

# convert files to desired file formats
build_pptx("slides/final-project-presentation.Rmd") # _html, _gif, _mp4, _png

