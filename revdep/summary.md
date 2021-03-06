# Setup

## Platform

|setting  |value                        |
|:--------|:----------------------------|
|version  |R version 3.2.3 (2015-12-10) |
|system   |x86_64, darwin13.4.0         |
|ui       |RStudio (0.99.875)           |
|language |(EN)                         |
|collate  |en_US.UTF-8                  |
|tz       |America/Chicago              |
|date     |2016-02-08                   |

## Packages

|package      |*  |version |date       |source         |
|:------------|:--|:-------|:----------|:--------------|
|dichromat    |   |2.0-0   |2013-01-24 |CRAN (R 3.2.0) |
|labeling     |   |0.3     |2014-08-23 |CRAN (R 3.2.0) |
|munsell      |   |0.4.2   |2013-07-11 |CRAN (R 3.2.0) |
|plyr         |   |1.8.3   |2015-06-12 |CRAN (R 3.2.0) |
|RColorBrewer |   |1.1-2   |2014-12-07 |CRAN (R 3.2.0) |
|Rcpp         |   |0.12.3  |2016-01-10 |CRAN (R 3.2.3) |
|testthat     |*  |0.11.0  |2015-10-14 |CRAN (R 3.2.0) |

# Check results
101 checked out of 101 dependencies 

## alakazam (0.2.2)
Maintainer: Jason Vander Heiden <jason.vanderheiden@yale.edu>  
Bug reports: https://bitbucket.org/kleinstein/alakazam/issues

0 errors | 0 warnings | 0 notes

## aqp (1.9.3)
Maintainer: Dylan Beaudette <debeaudette@ucdavis.edu>

0 errors | 0 warnings | 0 notes

## backtestGraphics (0.1.6)
Maintainer: Miller Zijie Zhu <zijie.miller.zhu@gmail.com>

0 errors | 0 warnings | 0 notes

## bdrift (1.1.7)
Maintainer: Markus Peter Auer <mp.auer@meanerreversion.com>  
Bug reports: http://github.com/MeanerReversion/bdrift/issues

0 errors | 0 warnings | 0 notes

## bdscale (1.2)
Maintainer: Dave Mills <dave.a.mills@gmail.com>

0 errors | 1 warning | 0 notes

```
checking whether package ‘bdscale’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘bdscale’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/bdscale.Rcheck/00install.out’ for details.
```

## benchmark (0.3-6)
Maintainer: Manuel J. A. Eugster <manuel@mjae.net>

0 errors | 1 warning | 4 notes

```
checking whether package ‘benchmark’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘benchmark’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/benchmark.Rcheck/00install.out’ for details.

checking package dependencies ... NOTE
Package suggested but not available for checking: ‘Rgraphviz’

checking dependencies in R code ... NOTE
'library' or 'require' call to ‘multcomp’ in package code.
  Please use :: or requireNamespace() instead.
  See section 'Suggested packages' in the 'Writing R Extensions' manual.

checking R code for possible problems ... NOTE
boxplot.AlgorithmPerformance: no visible binding for global variable
  ‘algorithms’
boxplot.AlgorithmPerformance: no visible binding for global variable
  ‘value’
boxplot.AlgorithmPerformance: no visible binding for global variable
  ‘samples’
bsgraph0.dist: no visible global function definition for ‘addEdge’
bsgraph0.graphNEL: no visible global function definition for
  ‘getDefaultAttrs’
bsgraph0.graphNEL: no visible global function definition for ‘agopen’
densityplot.AlgorithmPerformance: no visible binding for global
  variable ‘value’
densityplot.AlgorithmPerformance: no visible binding for global
  variable ‘algorithms’
mi: no visible global function definition for ‘mi.plugin’
patch.relation_class_ids: no visible global function definition for
  ‘relation_is_strict_weak_order’
plot.DatasetCharacterization: no visible binding for global variable
  ‘characteristics’
plot.DatasetCharacterization: no visible binding for global variable
  ‘value’
plot.DatasetCharacterization: no visible binding for global variable
  ‘samples’
plot.DatasetCharacterization: no visible global function definition for
  ‘theme_text’
plot.TestResult: no visible binding for global variable ‘samples’
plot.TestResult: no visible binding for global variable ‘value’
stripchart.AlgorithmPerformance: no visible binding for global variable
  ‘algorithms’
stripchart.AlgorithmPerformance: no visible binding for global variable
  ‘value’
stripchart.AlgorithmPerformance: no visible binding for global variable
  ‘samples’

checking Rd cross-references ... NOTE
Package unavailable to check Rd xrefs: ‘graph’
```

## bios2mds (1.2.2)
Maintainer: Marie Chabbert <marie.chabbert@univ-angers.fr>

0 errors | 0 warnings | 1 note

```
checking R code for possible problems ... NOTE
dis: no visible binding for global variable ‘sub.mat’
mat.dis: no visible binding for global variable ‘sub.mat’
mmds.3D.plot: no visible global function definition for ‘box3d’
mmds.3D.plot: no visible global function definition for ‘axes3d’

Found the following calls to data() loading into the global environment:
File ‘bios2mds/R/dis.R’:
  data("sub.mat", package = "bios2mds", verbose = FALSE)
File ‘bios2mds/R/mat.dis.R’:
  data("sub.mat", package = "bios2mds", verbose = FALSE)
See section ‘Good practice’ in ‘?data’.
```

## brainGraph (0.55.0)
Maintainer: Christopher G. Watson <cgwatson@bu.edu>  
Bug reports: 
        https://groups.google.com/forum/?hl=en#!forum/brainGraph-help

0 errors | 0 warnings | 0 notes

## choroplethr (3.4.0)
Maintainer: Ari Lamstein <arilamstein@gmail.com>  
Bug reports: https://github.com/arilamstein/choroplethr/issues

0 errors | 0 warnings | 0 notes

## chron (2.3-47)
Maintainer: Kurt Hornik <Kurt.Hornik@R-project.org>

0 errors | 0 warnings | 0 notes

## clhs (0.5-5)
Maintainer: Pierre Roudier <roudierp@landcareresearch.co.nz>

0 errors | 0 warnings | 0 notes

## clifro (2.4-0)
Maintainer: Blake Seers <blake.seers@gmail.com>  
Bug reports: https://github.com/ropensci/clifro/issues

0 errors | 0 warnings | 1 note

```
checking R code for possible problems ... NOTE
speed_plot,cfWind-missing : .local: no visible binding for global
  variable ‘speed’
speed_plot,cfWind-missing : .local: no visible binding for global
  variable ‘spd.sd’
```

## complmrob (0.6.1)
Maintainer: David Kepplinger <david.kepplinger@gmail.com>

0 errors | 0 warnings | 0 notes

## covmat (1.0)
Maintainer: Rohit Arora <emailrohitarora@gmail.com>

0 errors | 0 warnings | 0 notes

## d3heatmap (0.6.1)
Maintainer: Joe Cheng <joe@rstudio.com>  
Bug reports: https://github.com/rstudio/d3heatmap/issues

0 errors | 0 warnings | 0 notes

## Deducer (0.7-9)
Maintainer: Ian Fellows <ian@fellstat.com>

0 errors | 0 warnings | 0 notes

## DeducerSpatial (0.7)
Maintainer: Ian Fellows <ian@fellstat.com>

0 errors | 0 warnings | 6 notes

```
checking package dependencies ... NOTE
Depends: includes the non-default packages:
  ‘JavaGD’ ‘Deducer’ ‘sp’ ‘maptools’ ‘OpenStreetMap’ ‘scales’ ‘rgdal’
Adding so many packages to the search path is excessive and importing
selectively is preferable.

checking DESCRIPTION meta-information ... NOTE
Package listed in more than one of Depends, Imports, Suggests, Enhances:
  ‘UScensus2010’
A package should be listed in only one of these fields.

checking top-level files ... NOTE
Non-standard file/directory found at top level:
  ‘org’

checking dependencies in R code ... NOTE
'library' or 'require' call to ‘UScensus2010’ in package code.
  Please use :: or requireNamespace() instead.
  See section 'Suggested packages' in the 'Writing R Extensions' manual.
Namespace in Imports field not imported from: ‘UScensus2010’
  All declared Imports should be used.
Packages in Depends field not imported from:
  ‘JavaGD’ ‘OpenStreetMap’ ‘maptools’ ‘rgdal’ ‘scales’ ‘sp’
  These packages need to be imported from (in the NAMESPACE file)
  for when this namespace is loaded but not attached.

checking R code for possible problems ... NOTE
.containedBy: no visible global function definition for
  ‘projectMercator’
.makeCensusDialog: no visible global function definition for ‘J’
.makeCensusDialog: no visible global function definition for ‘.jnull’
.onLoad: no visible global function definition for ‘.jnull’
.onLoad: no visible global function definition for ‘.jpackage’
.onLoad: no visible global function definition for ‘.jengine’
.onLoad: no visible global function definition for ‘J’
.subsetLines: no visible global function definition for
  ‘projectMercator’
.subsetPoints: no visible global function definition for
  ‘projectMercator’
.subsetPoly: no visible global function definition for
  ‘projectMercator’
spatialBubblePlot: no visible global function definition for
  ‘coordinates’
spatialChoropleth: no visible global function definition for
  ‘manual_pal’
spatialChoropleth: no visible global function definition for
  ‘gradient_n_pal’
spatialChoropleth: no visible global function definition for ‘cscale’
spatialColoredPoints: no visible global function definition for
  ‘manual_pal’
spatialColoredPoints: no visible global function definition for
  ‘gradient_n_pal’
spatialColoredPoints: no visible global function definition for
  ‘cscale’
spatialTextPlot: no visible global function definition for
  ‘coordinates’

checking Rd line widths ... NOTE
Rd file 'loadCensusData.Rd':
  \usage lines wider than 90 characters:
                     year=c("2010","2000"), verbose=TRUE, osmTransform=TRUE, envir = .GlobalEnv)

Rd file 'spatialTextPlot.Rd':
  \examples lines wider than 100 characters:
     plot.window(c(-1.3160249151515616E7,-1.3155204307648793E7),c(3992993.9205893227,3996691.5618326175), xaxs = 'i', yaxs = 'i')
     plot(openmap(c(33.760525217369974,-118.22052955627441),c(33.73290566922855,-118.17521095275879),14,'bing'),add=TRUE)

These lines will be truncated in the PDF manual.
```

## DescribeDisplay (0.2.5)
Maintainer: Di Cook <dicook@monash.edu>  
Bug reports: https://github.com/ggobi/DescribeDisplay/issues

0 errors | 0 warnings | 0 notes

## DiagrammeR (0.8.2)
Maintainer: Richard Iannone <riannone@me.com>  
Bug reports: https://github.com/rich-iannone/DiagrammeR/issues

0 errors | 0 warnings | 1 note

```
checking installed package size ... NOTE
  installed size is  9.5Mb
  sub-directories of 1Mb or more:
    examples      2.4Mb
    htmlwidgets   4.6Mb
    img           2.2Mb
```

## disclapmix (1.6.2)
Maintainer: Mikkel Meyer Andersen <mikl@math.aau.dk>

0 errors | 0 warnings | 0 notes

## drc (2.5-12)
Maintainer: Christian Ritz <ritz@bioassay.dk>

0 errors | 0 warnings | 0 notes

## dslice (1.1.5)
Maintainer: Chao Ye <yechao1009@gmail.com>

0 errors | 0 warnings | 0 notes

## dtwSat (0.1.0)
Maintainer: Victor Maus <vwmaus1@gmail.com>

0 errors | 0 warnings | 0 notes

## EasyHTMLReport (0.1.1)
Maintainer: Yohei Sato <yohei0511@gmail.com>

0 errors | 0 warnings | 3 notes

```
checking top-level files ... NOTE
Non-standard files/directories found at top level:
  ‘easy_html_report_tmp_1376284934.59207.tsv’
  ‘easy_html_report_tmp_1376284935.5951.tsv’
  ‘easy_html_report_tmp_1376284936.59848.tsv’

checking dependencies in R code ... NOTE
Namespaces in Imports field not imported from:
  ‘ggplot2’ ‘reshape2’ ‘scales’ ‘xtable’
  All declared Imports should be used.
Packages in Depends field not imported from:
  ‘base64enc’ ‘knitr’ ‘markdown’
  These packages need to be imported from (in the NAMESPACE file)
  for when this namespace is loaded but not attached.

checking R code for possible problems ... NOTE
.file_attachment: no visible global function definition for
  ‘base64encode’
easyHtmlReport: no visible global function definition for ‘knit’
easyHtmlReport: no visible global function definition for
  ‘markdownToHTML’
```

## EpiBayes (0.1.2)
Maintainer: Matthew Branan <matthew.branan@gmail.com>

0 errors | 0 warnings | 0 notes

## extracat (1.7-4)
Maintainer: Alexander Pilhoefer <alexander.pilhoefer@gmail.com>

0 errors | 1 warning | 0 notes

```
checking whether package ‘extracat’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘ggplot2::unit’ when loading ‘extracat’
  Warning: replacing previous import by ‘ggplot2::arrow’ when loading ‘extracat’
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘extracat’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/extracat.Rcheck/00install.out’ for details.
```

## ez (4.3)
Maintainer: Michael A. Lawrence <mike.lwrnc@gmail.com>

0 errors | 0 warnings | 0 notes

## FAOSTAT (2.0)
Maintainer: Filippo Gheri <filippo.gheri@fao.org>

0 errors | 1 warning | 1 note

```
checking whether package ‘FAOSTAT’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘FAOSTAT’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/FAOSTAT.Rcheck/00install.out’ for details.

checking data for non-ASCII characters ... NOTE
  Note: found 179 marked UTF-8 strings
```

## fslr (1.5.0)
Maintainer: John Muschelli <muschellij2@gmail.com>  
Bug reports: https://github.com/muschellij2/fslr/issues

0 errors | 0 warnings | 0 notes

## fSRM (0.6.4)
Maintainer: Felix Schönbrodt <felix@nicebread.de>

0 errors | 0 warnings | 0 notes

## funModeling (1.0)
Maintainer: Pablo Casas <pabloc@datascienceheroes.com>

0 errors | 0 warnings | 0 notes

## GGally (1.0.1)
Maintainer: Barret Schloerke <schloerke@gmail.com>  
Bug reports: https://github.com/ggobi/ggally/issues

0 errors | 0 warnings | 1 note

```
checking installed package size ... NOTE
  installed size is  7.8Mb
  sub-directories of 1Mb or more:
    doc   6.8Mb
```

## ggalt (0.1.1)
Maintainer: Bob Rudis <bob@rudis.net>  
Bug reports: https://github.com/hrbrmstr/ggalt/issues

0 errors | 0 warnings | 0 notes

## ggfortify (0.1.0)
Maintainer: Masaaki Horikoshi <sinhrks@gmail.com>

0 errors | 0 warnings | 0 notes

## ggmap (2.6.1)
Maintainer: David Kahle <david.kahle@gmail.com>  
Bug reports: https://github.com/dkahle/ggmap/issues

0 errors | 0 warnings | 0 notes

## ggplot2 (2.0.0)
Maintainer: Hadley Wickham <hadley@rstudio.com>  
Bug reports: https://github.com/hadley/ggplot2/issues

0 errors | 0 warnings | 0 notes

## ggspectra (0.1.6)
Maintainer: Pedro J. Aphalo <pedro.aphalo@helsinki.fi>  
Bug reports: https://bitbucket.org/aphalo/ggspectra

0 errors | 0 warnings | 0 notes

## ggtern (2.0.1)
Maintainer: Nicholas Hamilton <nick@ggtern.com>

1 error | 0 warnings | 0 notes

```
checking examples ... ERROR
Running examples in ‘ggtern-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: convenience_functions
> ### Title: Theme Convenience Functions
> ### Aliases: convenience convenience_functions theme_convenience
> 
> ### ** Examples
> 
> 
> #Load data and create the base plot.
> data(Feldspar)
> plot <- ggtern(data=Feldspar,aes(x=An,y=Ab,z=Or)) + geom_point() + theme_bw()
> plot
Error in ggint$map_layout(panel, plot$facet, layer_data, plot$data) : 
  unused argument (plot$data)
Calls: <Anonymous> -> print.ggplot -> ggplot_build -> <Anonymous>
Execution halted
```

## ggthemes (3.0.1)
Maintainer: Jeffrey B. Arnold <jeffrey.arnold@gmail.com>  
Bug reports: http://github.com/jrnold/ggthemes

0 errors | 0 warnings | 0 notes

## gmwm (1.0.0)
Maintainer: Stephane Guerrier <stephane@illinois.edu>  
Bug reports: https://github.com/SMAC-Group/gmwm/issues

0 errors | 1 warning | 0 notes

```
checking whether package ‘gmwm’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘grid::arrow’ when loading ‘gmwm’
  Warning: replacing previous import by ‘grid::unit’ when loading ‘gmwm’
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘gmwm’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/gmwm.Rcheck/00install.out’ for details.
```

## gsDesign (3.0-1)
Maintainer: Keaven Anderson <keaven_anderson@merck.com>

0 errors | 0 warnings | 1 note

```
checking R code for possible problems ... NOTE
plotgsCP: no visible global function definition for ‘opts’
plotgsPower: no visible global function definition for ‘opts’
qplotit: no visible global function definition for ‘opts’
```

## igraph (1.0.1)
Maintainer: Gabor Csardi <csardi.gabor@gmail.com>  
Bug reports: https://github.com/igraph/igraph/issues

0 errors | 0 warnings | 2 notes

```
checking package dependencies ... NOTE
Package suggested but not available for checking: ‘graph’

checking installed package size ... NOTE
  installed size is  7.3Mb
  sub-directories of 1Mb or more:
    help   1.2Mb
    libs   4.5Mb
```

## inbreedR (0.3.0)
Maintainer: Martin A. Stoffel <martin.adam.stoffel@gmail.com>

0 errors | 0 warnings | 0 notes

## ldatuning (0.1.0)
Maintainer: Murzintcev Nikita <nikita@lreis.ac.cn>  
Bug reports: https://github.com/nikita-moor/ldatuning/issues

0 errors | 0 warnings | 0 notes

## leaflet (1.0.0)
Maintainer: Joe Cheng <joe@rstudio.com>  
Bug reports: https://github.com/rstudio/leaflet/issues

0 errors | 0 warnings | 0 notes

## likeLTD (6.0.2)
Maintainer: Christopher Steele <c.steele.11@ucl.ac.uk>

0 errors | 0 warnings | 0 notes

## mapview (1.0.0)
Maintainer: Tim Appelhans <admin@environmentalinformatics-marburg.de>

0 errors | 0 warnings | 0 notes

## multitable (1.6)
Maintainer: Steve C Walker <steve.walker@utoronto.ca>

1 error | 0 warnings | 1 note

```
checking running R code from vignettes ... ERROR
Errors in running code in vignettes:
when running code in ‘multitable.Rnw’
  ...
> p <- p + geom_point(aes(x = width, y = abundance, 
+     shape = life.history))

> p <- p + stat_smooth(aes(x = width, y = abundance), 
+     se = FALSE, method = "bayesglm", family = poisson, form = y ~ 
+         x + I(x^2), colo .... [TRUNCATED] 

  When sourcing ‘multitable.R’:
Error: Unknown parameters: family, form
Execution halted


checking re-building of vignette outputs ... NOTE
Error in re-building vignettes:
  ...
The following object is masked from ‘package:arm’:

    rescale

dimids automatically generated
dimids automatically generated
omitting width because it is not replicated along MARGIN
omitting temp because it is not replicated along MARGIN
omitting depth because it is not replicated along MARGIN
omitting velocity because it is not replicated along MARGIN
omitting substrate because it is not replicated along MARGIN
omitting habitat because it is not replicated along MARGIN
omitting trophic because of the following error:
 Error in median.default(newX[, i], ...) : need numeric data

omitting life.history because of the following error:
 Error in median.default(newX[, i], ...) : need numeric data

omitting trophic because it is not replicated along MARGIN
omitting life.history because it is not replicated along MARGIN

Error: processing vignette 'multitable.Rnw' failed with diagnostics:
 chunk 57 (label = a faceted ggplot scatterplot from a data list) 
Error : Unknown parameters: family, form
Execution halted

```

## ncappc (0.2.1.0)
Maintainer: Chayan Acharya <chayan.acharya@farmbio.uu.se>

0 errors | 1 warning | 0 notes

```
checking whether package ‘ncappc’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘grid::arrow’ when loading ‘ncappc’
  Warning: replacing previous import by ‘grid::unit’ when loading ‘ncappc’
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘ncappc’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/ncappc.Rcheck/00install.out’ for details.
```

## NeuralNetTools (1.4.0)
Maintainer: Marcus W. Beck <mbafs2012@gmail.com>  
Bug reports: https://github.com/fawda123/NeuralNetTools/issues

0 errors | 1 warning | 0 notes

```
checking whether package ‘NeuralNetTools’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘NeuralNetTools’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/NeuralNetTools.Rcheck/00install.out’ for details.
```

## NlsyLinks (2.0.1)
Maintainer: Will Beasley <wibeasley@hotmail.com>  
Bug reports: https://github.com/LiveOak/NlsyLinks/issues

0 errors | 0 warnings | 1 note

```
checking installed package size ... NOTE
  installed size is  6.3Mb
  sub-directories of 1Mb or more:
    data   4.3Mb
    doc    1.0Mb
```

## optiRum (0.37.3)
Maintainer: Stephanie Locke <stephanie.g.locke@gmail.com>  
Bug reports: https://github.com/stephlocke/optiRum/issues

0 errors | 0 warnings | 0 notes

## OutbreakTools (0.1-14)
Maintainer: Thibaut Jombart <thibautjombart@gmail.com>

0 errors | 0 warnings | 0 notes

## paleobioDB (0.3)
Maintainer: Sara Varela <svarela@paleobiogeography.org>  
Bug reports: https://github.com/ropensci/paleobioDB/issues

0 errors | 0 warnings | 1 note

```
checking DESCRIPTION meta-information ... NOTE
Malformed Description field: should contain one or more complete sentences.
```

## pheatmap (1.0.8)
Maintainer: Raivo Kolde <rkolde@gmail.com>

0 errors | 0 warnings | 0 notes

## plotKML (0.5-5)
Maintainer: Tomislav Hengl <tom.hengl@isric.org>

0 errors | 0 warnings | 0 notes

## plotly (2.0.16)
Maintainer: Carson Sievert <cpsievert1@gmail.com>  
Bug reports: https://github.com/ropensci/plotly/issues

1 error | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  [1] "Running test: histogram-fixed-fill-color"
  [1] "Running test: histogram-density-binwidth"
  [1] "Running test: histogram-fill-factor"
  [1] "Running test: histogram-fill-factor-identity"
  [1] "Running test: histogram-fill-factor-dodge"
  [1] "Running test: histogram-fill-factor-facets"
  [1] "Running test: histogram-vline"
  [1] "Running test: histogram-dates"
  14. Failure (at test-ggplot-histogram.R#136): dates work well with histograms --
  info$layout$xaxis$type is not identical to "date". Differences: 
  1 string mismatch
  
  [1] "Running test: histogram-POSIXt-bins"
```

## precintcon (2.2.1)
Maintainer: Lucas Venezian Povoa <lucasvenez@gmail.com>  
Bug reports: https://github.com/lucasvenez/precintcon/issues

0 errors | 0 warnings | 0 notes

## primerTree (1.0.3)
Maintainer: Jim Hester <james.f.hester@gmail.com>

0 errors | 0 warnings | 0 notes

## qdap (2.2.4)
Maintainer: Tyler Rinker <tyler.rinker@gmail.com>  
Bug reports: http://github.com/trinker/qdap/issues

0 errors | 0 warnings | 0 notes

## qicharts (0.4.3)
Maintainer: Jacob Anhoej <jacob@anhoej.net>

0 errors | 0 warnings | 0 notes

## quadrupen (0.2-4)
Maintainer: Julien Chiquet <julien.chiquet@genopole.cnrs.fr>

0 errors | 1 warning | 1 note

```
checking whether package ‘quadrupen’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘grid::arrow’ when loading ‘quadrupen’
  Warning: replacing previous import by ‘grid::unit’ when loading ‘quadrupen’
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘quadrupen’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/quadrupen.Rcheck/00install.out’ for details.

checking R code for possible problems ... NOTE
plot,cvpen : .local: no visible binding for global variable ‘lambda1’
plot,cvpen : .local: no visible binding for global variable ‘lambda2’
plot,cvpen : .local: no visible binding for global variable ‘serr’
plot,cvpen : .local: no visible binding for global variable ‘xval’
plot,cvpen : .local: no visible binding for global variable
  ‘lambda.choice’
plot,quadrupen : .local: no visible binding for global variable
  ‘variables’
plot,stability.path : .local: no visible binding for global variable
  ‘variables’
```

## quantable (0.1)
Maintainer: Witold Wolski <wewolski@gmail.com>  
Bug reports: https://github.com/wolski/quantable/issues

0 errors | 0 warnings | 0 notes

## R6 (2.1.2)
Maintainer: Winston Chang <winston@stdout.org>

0 errors | 0 warnings | 0 notes

## RAM (1.2.1.3)
Maintainer: Wen Chen <Wen.Chen@agr.gc.ca>  
Bug reports: https://bitbucket.org/Wen_Chen/ram_releases/issues/

0 errors | 0 warnings | 2 notes

```
checking package dependencies ... NOTE
Package suggested but not available for checking: ‘Heatplus’

checking Rd cross-references ... NOTE
Package unavailable to check Rd xrefs: ‘Heatplus’
```

## rAvis (0.1.4)
Maintainer: Sara Varela <svarela@paleobiogeography.org>  
Bug reports: https://github.com/ropensci/rAvis/issues

0 errors | 1 warning | 0 notes

```
checking whether package ‘rAvis’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘sp::nowrapSpatialLines’ when loading ‘rAvis’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/rAvis.Rcheck/00install.out’ for details.
```

## RcmdrPlugin.KMggplot2 (0.2-3)
Maintainer: Triad sou. <triadsou@gmail.com>

0 errors | 0 warnings | 0 notes

## RcmdrPlugin.MA (0.0-2)
Maintainer: A. C. Del Re <acdelre@gmail.com>

0 errors | 0 warnings | 0 notes

## RDS (0.7-4)
Maintainer: Mark S. Handcock <handcock@stat.ucla.edu>

0 errors | 0 warnings | 0 notes

## RImagePalette (0.1.1)
Maintainer: Joel Carlson <jnkcarlson@gmail.com>

0 errors | 0 warnings | 0 notes

## rnoaa (0.5.2)
Maintainer: Scott Chamberlain <myrmecocystus@gmail.com>  
Bug reports: http://www.github.com/ropensci/rnoaa/issues

0 errors | 0 warnings | 0 notes

## rollply (0.4.2)
Maintainer: Alexandre Genin <alex@lecairn.org>  
Bug reports: https://github.com/alexgenin/rollply

0 errors | 0 warnings | 0 notes

## RSDA (1.3)
Maintainer: Oldemar Rodriguez <oldemar.rodriguez@ucr.ac.cr>

0 errors | 1 warning | 0 notes

```
checking whether package ‘RSDA’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘RSDA’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/RSDA.Rcheck/00install.out’ for details.
```

## rsvd (0.3)
Maintainer: N. Benjamin Erichson <nbe@st-andrews.ac.uk>  
Bug reports: https://github.com/Benli11/rPCA

0 errors | 0 warnings | 0 notes

## rtimes (0.3.0)
Maintainer: Scott Chamberlain <myrmecocystus@gmail.com>  
Bug reports: https://github.com/ropengov/rtimes/issues

0 errors | 0 warnings | 0 notes

## SACOBRA (0.7)
Maintainer: Samineh Bagheri <samineh.bagheri@fh-koeln.de>

0 errors | 0 warnings | 0 notes

## SciencesPo (1.3.9)
Maintainer: Daniel Marcelino <dmarcelino@live.com>  
Bug reports: http://github.com/danielmarcelino/SciencesPo/issues

1 error | 0 warnings | 1 note

```
checking examples ... ERROR
Running examples in ‘SciencesPo-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: theme_pub
> ### Title: The Default Theme
> ### Aliases: theme_pub
> 
> ### ** Examples
> 
> ggplot(diamonds,aes(cut, group=1)) + geom_bar()+
+ geom_freqpoly(stat="count",size=2) + scale_color_pub() + theme_pub(line_width=1)
Error: Unknown parameters: pad
Execution halted

checking re-building of vignette outputs ... NOTE
Error in re-building vignettes:
  ...
Units                 Measurement System Units
bhodrick93            Bekaert's and Hodrick's (1993) Data
cathedrals            Cathedrals
cgreene76             Christensen's and Greene's (1976) Data
galton                Galton's Family Data on Human Stature.
griliches76           Griliches's (1976) Data
ltaylor96             Lothian's and Taylor's (1996) Data Set
marriage              Same Sex Marriage Public Opinion Data
mishkin92             Mishkin's (1992) Data
nerlove63             Marc Nerlove's (1963) data
paired                Paired Data
sheston91             The Penn World Table
swatson93             Stock's and Watson's (1993) Data.
titanic               Titanic
turnout               Turnout Data
twins                 Burt's twin data
words                 Word frequencies from Mosteller and Wallace

Loading required package: SciencesPo
initializing ... done

Quitting from lines 395-399 (SciencesPo.Rmd) 
Error: processing vignette 'SciencesPo.Rmd' failed with diagnostics:
polygon edge not found
Execution halted

```

## SEERaBomb (2015.2)
Maintainer: Tomas Radivoyevitch <radivot@ccf.org>

0 errors | 0 warnings | 0 notes

## sharpshootR (0.9.1)
Maintainer: Dylan Beaudette <dylan.beaudette@ca.usda.gov>

0 errors | 0 warnings | 0 notes

## simmer (3.1.2)
Maintainer: Iñaki Ucar <i.ucar86@gmail.com>  
Bug reports: https://github.com/Bart6114/simmer/issues

0 errors | 0 warnings | 0 notes

## SixSigma (0.9-2)
Maintainer: Emilio L. Cano <emilio.lopez@urjc.es>

0 errors | 0 warnings | 0 notes

## sjPlot (1.9.1)
Maintainer: Daniel Lüdecke <d.luedecke@uke.de>  
Bug reports: https://github.com/sjPlot/devel/issues

0 errors | 0 warnings | 0 notes

## soil.spec (2.1.4)
Maintainer: Andrew Sila <a.sila@cgiar.org>

0 errors | 0 warnings | 2 notes

```
checking dependencies in R code ... NOTE
'library' or 'require' calls in package code:
  ‘chemometrics’ ‘spatstat’
  Please use :: or requireNamespace() instead.
  See section 'Suggested packages' in the 'Writing R Extensions' manual.

checking S3 generic/method consistency ... NOTE
Found the following apparent S3 methods exported but not registered:
  plot.Spectra plot.ken.sto plot.trans predict.SpectraPoints
See section ‘Registering S3 methods’ in the ‘Writing R Extensions’
manual.
```

## solarius (0.3.0.2)
Maintainer: Andrey Ziyatdinov <andrey.ziyatdinov@upc.edu>

0 errors | 0 warnings | 0 notes

## spikeSlabGAM (1.1-9)
Maintainer: Fabian Scheipl
 <fabian.scheipl@stat.uni-muenchen.de>

0 errors | 1 warning | 0 notes

```
checking whether package ‘spikeSlabGAM’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘spikeSlabGAM’
  Warning: replacing previous import by ‘grid::unit’ when loading ‘spikeSlabGAM’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/spikeSlabGAM.Rcheck/00install.out’ for details.
```

## starma (1.2)
Maintainer: Felix Cheysson <felix@cheysson.fr>

0 errors | 1 warning | 0 notes

```
checking whether package ‘starma’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import by ‘scales::alpha’ when loading ‘starma’
See ‘/private/tmp/RtmpbLJwZN/check_cran45381ce01a1e/starma.Rcheck/00install.out’ for details.
```

## statebins (1.2.2)
Maintainer: Bob Rudis <bob@rudis.net>  
Bug reports: https://github.com/hrbrmstr/statebins/issues

0 errors | 0 warnings | 0 notes

## strvalidator (1.6.0)
Maintainer: Oskar Hansson <oskar.hansson@fhi.no>  
Bug reports: https://github.com/OskarHansson/strvalidator/issues

0 errors | 0 warnings | 0 notes

## surveillance (1.10-0)
Maintainer: Sebastian Meyer <Sebastian.Meyer@ifspm.uzh.ch>  
Bug reports: https://r-forge.r-project.org/tracker/?group_id=45

0 errors | 0 warnings | 1 note

```
checking package dependencies ... NOTE
Package suggested but not available for checking: ‘INLA’
```

## survminer (0.1.1)
Maintainer: Alboukadel Kassambara <alboukadel.kassambara@gmail.com>  
Bug reports: https://github.com/kassambara/survminer/issues

0 errors | 0 warnings | 0 notes

## svdvis (0.1)
Maintainer: Neo Christopher Chung <nchchung@gmail.com>

0 errors | 0 warnings | 0 notes

## tcR (2.2.1.7)
Maintainer: Vadim Nazarov <vdm.nazarov@gmail.com>  
Bug reports: https://github.com/imminfo/tcr/issues

0 errors | 0 warnings | 2 notes

```
checking installed package size ... NOTE
  installed size is  5.6Mb
  sub-directories of 1Mb or more:
    data   1.2Mb
    doc    3.9Mb

checking dependencies in R code ... NOTE
Namespace in Imports field not imported from: ‘scales’
  All declared Imports should be used.
```

## TDA (1.4.1)
Maintainer: Jisu Kim <jisuk1@andrew.cmu.edu>

0 errors | 0 warnings | 2 notes

```
checking dependencies in R code ... NOTE
Namespace in Imports field not imported from: ‘scales’
  All declared Imports should be used.

checking compiled code ... NOTE
File ‘TDA/libs/TDA.so’:
  Found ‘__ZNSt3__14coutE’, possibly from ‘std::cout’ (C++)
    Object: ‘diag.o’

Compiled code should not call entry points which might terminate R nor
write to stdout/stderr instead of to the console, nor the system RNG.

See ‘Writing portable packages’ in the ‘Writing R Extensions’ manual.
```

## tis (1.30)
Maintainer: Jeff Hallman <jeffrey.j.hallman@frb.gov>

0 errors | 0 warnings | 0 notes

## toaster (0.4.2)
Maintainer: Gregory Kanevsky <gregory.kanevsky@teradata.com>  
Bug reports: https://github.com/teradata-aster-field/toaster/issues

1 error | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RODBC’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## TriMatch (0.9.6)
Maintainer: Jason Bryer <jason@bryer.org>  
Bug reports: https://github.com/jbryer/TriMatch/issues

0 errors | 0 warnings | 0 notes

## useful (1.2.0)
Maintainer: Jared P. Lander <packages@jaredlander.com>

0 errors | 0 warnings | 0 notes

## vetools (1.3-28)
Maintainer: Andrew Sajo-Castelli <asajo@usb.ve>  
Bug reports: https://github.com/talassio/vetools/issues

0 errors | 0 warnings | 0 notes

## viridis (0.3.2)
Maintainer: Simon Garnier <garnier@njit.edu>  
Bug reports: https://github.com/sjmgarnier/viridis/issues

0 errors | 0 warnings | 0 notes

## Wats (0.10.3)
Maintainer: Will Beasley <wibeasley@hotmail.com>  
Bug reports: https://github.com/OuhscBbmc/Wats/issues

0 errors | 0 warnings | 0 notes

## zoo (1.7-12)
Maintainer: Achim Zeileis <Achim.Zeileis@R-project.org>

0 errors | 0 warnings | 1 note

```
checking Rd cross-references ... NOTE
Package unavailable to check Rd xrefs: ‘stinepack’
```

