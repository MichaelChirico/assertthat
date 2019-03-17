# afmToolkit

Version: 0.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DBI’ ‘assertthat’ ‘tibble’
      All declared Imports should be used.
    ```

# antaresViz

Version: 0.15.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        R             2.1Mb
        doc           2.0Mb
        htmlwidgets   1.1Mb
    ```

# AntWeb

Version: 0.7

## In both

*   checking R code for possible problems ... NOTE
    ```
    aw_map: no visible global function definition for ‘browseURL’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/AntWeb/new/AntWeb.Rcheck/00_pkg_src/AntWeb/R/aw_map.R:52)
    Undefined global functions or variables:
      browseURL
    Consider adding
      importFrom("utils", "browseURL")
    to your NAMESPACE file.
    ```

# auk

Version: 0.3.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 552 marked UTF-8 strings
    ```

# awsjavasdk

Version: 0.2.0

## In both

*   checking whether package ‘awsjavasdk’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/awsjavasdk/new/awsjavasdk.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘awsjavasdk’ ...
** package ‘awsjavasdk’ successfully unpacked and MD5 sums checked
** R
** inst
** byte-compile and prepare package for lazy loading
Error : .onLoad failed in loadNamespace() for 'rJava', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/awsjavasdk/rJava/libs/rJava.so':
  dlopen(/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/awsjavasdk/rJava/libs/rJava.so, 6): Library not loaded: /Library/Java/JavaVirtualMachines/jdk-11.0.1.jdk/Contents/Home/lib/server/libjvm.dylib
  Referenced from: /Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/awsjavasdk/rJava/libs/rJava.so
  Reason: image not found
ERROR: lazy loading failed for package ‘awsjavasdk’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/awsjavasdk/new/awsjavasdk.Rcheck/awsjavasdk’

```
### CRAN

```
* installing *source* package ‘awsjavasdk’ ...
** package ‘awsjavasdk’ successfully unpacked and MD5 sums checked
** R
** inst
** byte-compile and prepare package for lazy loading
Error : .onLoad failed in loadNamespace() for 'rJava', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/awsjavasdk/rJava/libs/rJava.so':
  dlopen(/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/awsjavasdk/rJava/libs/rJava.so, 6): Library not loaded: /Library/Java/JavaVirtualMachines/jdk-11.0.1.jdk/Contents/Home/lib/server/libjvm.dylib
  Referenced from: /Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/awsjavasdk/rJava/libs/rJava.so
  Reason: image not found
ERROR: lazy loading failed for package ‘awsjavasdk’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/awsjavasdk/old/awsjavasdk.Rcheck/awsjavasdk’

```
# bigQueryR

Version: 0.4.0

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available: ‘googleAuthR’ ‘googleCloudStorageR’
    
    Packages suggested but not available for checking: ‘shiny’ ‘data.table’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# binman

Version: 0.1.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘semver’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# biofiles

Version: 1.0.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘reutils’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# BPRMeth

Version: 1.8.1

## In both

*   checking whether package ‘BPRMeth’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/BPRMeth/new/BPRMeth.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘BPRMeth’ ...
** libs
clang++ -std=gnu++11 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG  -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/BPRMeth/Rcpp/include" -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/BPRMeth/RcppArmadillo/include" -I/usr/local/include  -fopenmp  -fPIC  -Wall -g -O2 -c RcppExports.cpp -o RcppExports.o
clang: error: unsupported option '-fopenmp'
make: *** [RcppExports.o] Error 1
ERROR: compilation failed for package ‘BPRMeth’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/BPRMeth/new/BPRMeth.Rcheck/BPRMeth’

```
### CRAN

```
* installing *source* package ‘BPRMeth’ ...
** libs
clang++ -std=gnu++11 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG  -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/BPRMeth/Rcpp/include" -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/BPRMeth/RcppArmadillo/include" -I/usr/local/include  -fopenmp  -fPIC  -Wall -g -O2 -c RcppExports.cpp -o RcppExports.o
clang: error: unsupported option '-fopenmp'
make: *** [RcppExports.o] Error 1
ERROR: compilation failed for package ‘BPRMeth’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/BPRMeth/old/BPRMeth.Rcheck/BPRMeth’

```
# breathtestcore

Version: 0.4.6

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘breathteststan’
    ```

# bulletcp

Version: 1.0.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘Rdpack’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# CAGEfightR

Version: 1.2.0

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available:
      ‘Matrix.utils’ ‘grr’ ‘GenomicFeatures’ ‘InteractionSet’
      ‘GenomicInteractions’
    
    Packages suggested but not available for checking:
      ‘org.Mm.eg.db’ ‘TxDb.Mmusculus.UCSC.mm9.knownGene’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# CausalImpact

Version: 1.2.3

## In both

*   checking R code for possible problems ... NOTE
    ```
    ConstructModel: warning in AddDynamicRegression(ss, formula, data =
      data, sigma.mean.prior = sigma.mean.prior): partial argument match of
      'sigma.mean.prior' to 'sigma.mean.prior.DEPRECATED'
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/CausalImpact/new/CausalImpact.Rcheck/00_pkg_src/CausalImpact/R/impact_model.R:232-233)
    ```

# cicero

Version: 1.0.15

## Newly fixed

*   R CMD check timed out
    

## In both

*   checking R code for possible problems ... NOTE
    ```
    aggregate_nearby_peaks: no visible binding for global variable 'val'
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/cicero/new/cicero.Rcheck/00_pkg_src/cicero/R/aggregate.R:37)
    assemble_connections: no visible binding for global variable 'value'
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/cicero/new/cicero.Rcheck/00_pkg_src/cicero/R/runCicero.R:640-641)
    find_overlapping_ccans: no visible binding for global variable 'CCAN'
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/cicero/new/cicero.Rcheck/00_pkg_src/cicero/R/runCicero.R:919-922)
    generate_windows: no visible binding for global variable 'V1'
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/cicero/new/cicero.Rcheck/00_pkg_src/cicero/R/runCicero.R:663-667)
    plot_accessibility_in_pseudotime: no visible binding for global
      variable 'f_id'
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/cicero/new/cicero.Rcheck/00_pkg_src/cicero/R/plotting.R:676-695)
    Undefined global functions or variables:
      CCAN V1 f_id val value
    ```

# circumplex

Version: 0.2.1

## In both

*   checking whether package ‘circumplex’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/circumplex/new/circumplex.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘circumplex’ ...
** package ‘circumplex’ successfully unpacked and MD5 sums checked
** libs
clang++ -std=gnu++11 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG  -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/circumplex/Rcpp/include" -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/circumplex/RcppArmadillo/include" -I/usr/local/include  -fopenmp  -fPIC  -Wall -g -O2 -c RcppExports.cpp -o RcppExports.o
clang: error: unsupported option '-fopenmp'
make: *** [RcppExports.o] Error 1
ERROR: compilation failed for package ‘circumplex’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/circumplex/new/circumplex.Rcheck/circumplex’

```
### CRAN

```
* installing *source* package ‘circumplex’ ...
** package ‘circumplex’ successfully unpacked and MD5 sums checked
** libs
clang++ -std=gnu++11 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG  -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/circumplex/Rcpp/include" -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/circumplex/RcppArmadillo/include" -I/usr/local/include  -fopenmp  -fPIC  -Wall -g -O2 -c RcppExports.cpp -o RcppExports.o
clang: error: unsupported option '-fopenmp'
make: *** [RcppExports.o] Error 1
ERROR: compilation failed for package ‘circumplex’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/circumplex/old/circumplex.Rcheck/circumplex’

```
# citr

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘bibtex’
      All declared Imports should be used.
    ```

# CTRE

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tea’
      All declared Imports should be used.
    ```

# DChIPRep

Version: 1.12.0

## In both

*   checking whether package ‘DChIPRep’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/DChIPRep/new/DChIPRep.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘DChIPRep’ ...
** R
** data
*** moving datasets to lazyload DB
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
** exec
** inst
** byte-compile and prepare package for lazy loading
Error in loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]]) : 
  there is no package called ‘GO.db’
ERROR: lazy loading failed for package ‘DChIPRep’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/DChIPRep/new/DChIPRep.Rcheck/DChIPRep’

```
### CRAN

```
* installing *source* package ‘DChIPRep’ ...
** R
** data
*** moving datasets to lazyload DB
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
Warning: namespace ‘DChIPRep’ is not available and has been replaced
by .GlobalEnv when processing object ‘testData’
** exec
** inst
** byte-compile and prepare package for lazy loading
Error in loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]]) : 
  there is no package called ‘GO.db’
ERROR: lazy loading failed for package ‘DChIPRep’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/DChIPRep/old/DChIPRep.Rcheck/DChIPRep’

```
# DEP

Version: 1.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        R      1.2Mb
        data   1.4Mb
        doc    3.1Mb
    ```

# detrendr

Version: 0.6.0

## In both

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# disto

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘proxy’
      All declared Imports should be used.
    ```

# dplyr

Version: 0.8.0.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.8Mb
      sub-directories of 1Mb or more:
        R      2.1Mb
        libs   3.0Mb
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4 marked UTF-8 strings
    ```

# dynutils

Version: 1.0.1

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      [31m──[39m [31m1. Error: has_names works (@test-assertions.R#43) [39m [31m────────────────────────────[39m
      multiple values passed to has_name
      1: expect_true(list(a = 1, b = 2) %has_names% c("a", "b")) at testthat/test-assertions.R:43
      2: quasi_label(enquo(object), label)
      3: eval_bare(get_expr(quo), get_env(quo))
      4: list(a = 1, b = 2) %has_names% c("a", "b")
      5: x %has_name% which at /Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/dynutils/new/dynutils.Rcheck/00_pkg_src/dynutils/R/assertions.R:107
      6: assert_that(is.scalar(which), msg = "multiple values passed to has_name") at /private/tmp/Rtmp4LvShU/R.INSTALLccd4176bf73a/assertthat/R/assertions.r:46
      
      ══ testthat results  ═════════════════════════════════════════════════════════════
      OK: 476 SKIPPED: 1 FAILED: 1
      1. Error: has_names works (@test-assertions.R#43) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# ecoengine

Version: 1.11.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# ExpDE

Version: 0.1.4

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    The error most likely occurred in:
    
    > ### Name: ExpDE
    > ### Title: Experimental Differential Evolution - ExpDE
    > ### Aliases: ExpDE
    > 
    > ### ** Examples
    > 
    > # DE/rand/1/bin with population 40, F = 0.8 and CR = 0.5
    > popsize  <- 100
    > mutpars  <- list(name = "mutation_rand", f = 0.8)
    > recpars  <- list(name = "recombination_bin", cr = 0.5, minchange = TRUE)
    > selpars  <- list(name = "selection_standard")
    > stopcrit <- list(names = "stop_maxiter", maxiter = 100)
    > probpars <- list(name  = "sphere",
    +                 xmin = rep(-5.12,10), xmax = rep(5.12,10))
    > seed <- NULL
    > showpars <- list(show.iters = "numbers", showevery = 1)
    > ExpDE(popsize, mutpars, recpars, selpars, stopcrit, probpars, seed, showpars)
    Error: multiple values passed to has_name
    Execution halted
    ```

# gastempt

Version: 0.4.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.7Mb
      sub-directories of 1Mb or more:
        libs   7.2Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘methods’ ‘rstantools’
      All declared Imports should be used.
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# GeneAccord

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.2Mb
      sub-directories of 1Mb or more:
        data      3.0Mb
        doc       1.0Mb
        extdata   6.5Mb
    ```

# GerminaR

Version: 1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘shinydashboard’
      All declared Imports should be used.
    ```

# glmmfields

Version: 0.1.2

## In both

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# googleAuthR

Version: 0.7.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘R6’
      All declared Imports should be used.
    ```

# grattan

Version: 1.7.0.0

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘taxstats’ ‘taxstats1516’
    ```

# heatmaply

Version: 0.15.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        doc   4.6Mb
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘d3heatmap’
    ```

# highcharter

Version: 0.7.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.2Mb
      sub-directories of 1Mb or more:
        doc           3.7Mb
        htmlwidgets   4.0Mb
    ```

# HMP16SData

Version: 1.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Attaching package: 'dendextend'
    
    The following object is masked from 'package:stats':
    
        cutree
    
    ========================================
    circlize version 0.4.5
    CRAN page: https://cran.r-project.org/package=circlize
    Github page: https://github.com/jokergoo/circlize
    Documentation: http://jokergoo.github.io/circlize_book/book/
    
    If you use it in published research, please cite:
    Gu, Z. circlize implements and enhances circular visualization 
      in R. Bioinformatics 2014.
    ========================================
    
    Quitting from lines 58-71 (HMP16SData.Rmd) 
    Error: processing vignette 'HMP16SData.Rmd' failed with diagnostics:
    there is no package called 'curatedMetagenomicData'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘curatedMetagenomicData’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 19.1Mb
      sub-directories of 1Mb or more:
        doc       1.5Mb
        extdata  17.4Mb
    ```

# huxtable

Version: 4.4.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      Fontconfig error: "/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/huxtable/magick/etc/fonts/conf.d/90-synthetic.conf", line 6: invalid attribute 'version'
      Fontconfig error: Cannot load default config file
      [31m──[39m [31m1. Failure: huxreg copes with different models (@test-huxreg.R#31) [39m [31m───────────[39m
      `hr <- huxreg(lm1, lm2, glm1)` produced warnings.
      
      [31m──[39m [31m2. Failure: Data written in appropriate format (@test-openxlsx.R#101) [39m [31m────────[39m
      `openxlsx::saveWorkbook(wb, file = "test-xlsx.xlsx", overwrite = TRUE)` produced messages.
      
      ══ testthat results  ═════════════════════════════════════════════════════════════
      OK: 888 SKIPPED: 57 FAILED: 2
      1. Failure: huxreg copes with different models (@test-huxreg.R#31) 
      2. Failure: Data written in appropriate format (@test-openxlsx.R#101) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        R     2.1Mb
        doc   2.9Mb
    ```

# kdensity

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘EQL’ ‘knitr’ ‘rmarkdown’
      All declared Imports should be used.
    ```

# MOEADr

Version: 1.1.0

## Newly broken

*   checking examples ... ERROR
    ```
    Running examples in ‘MOEADr-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: create_population
    > ### Title: Create population
    > ### Aliases: create_population
    > 
    > ### ** Examples
    > 
    > ex.problem <- list(name = "example_problem",
    +                    xmin = rep(-1, 5),
    +                    xmax = rep(1, 5),
    +                    m    = 2)
    > X <- create_population(20, ex.problem)
    Error: multiple values passed to has_name
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 65-70 (Basic_Usage.Rmd) 
    Error: processing vignette 'Basic_Usage.Rmd' failed with diagnostics:
    multiple values passed to has_name
    Execution halted
    ```

# MonetDBLite

Version: 0.6.0

## Newly fixed

*   R CMD check timed out
    

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.1Mb
      sub-directories of 1Mb or more:
        libs   5.4Mb
    ```

# nandb

Version: 2.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘MASS’ ‘stats’
      All declared Imports should be used.
    ```

# nima

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ProjectTemplate’ ‘devtools’ ‘plyr’ ‘survival’
      All declared Imports should be used.
    ```

# paramlink

Version: 1.1-2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘Familias’
    ```

# perturbatr

Version: 1.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.9Mb
      sub-directories of 1Mb or more:
        data   3.8Mb
    ```

# phantasus

Version: 1.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 14.9Mb
      sub-directories of 1Mb or more:
        doc   2.6Mb
        www  11.5Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      'GEOquery:::getDirListing' 'opencpu:::rookhandler'
      'opencpu:::tmp_root' 'opencpu:::win_or_mac'
      See the note in ?`:::` about the use of this operator.
    ```

# pivot

Version: 18.4.17

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘odbc’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘colorspace’ ‘lubridate’
      All declared Imports should be used.
    ```

# pkgcache

Version: 1.0.3

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      1: read_packages_file(pf[1], mirror = "m1", repodir = "r1", platform = "source", rversion = "*") at testthat/test-packages-gz.R:88
      2: as_tibble(read.dcf.gz(path)) at /Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/pkgcache/new/pkgcache.Rcheck/00_pkg_src/pkgcache/R/packages-gz.R:19
      3: read.dcf.gz(path) at /Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/pkgcache/new/pkgcache.Rcheck/00_pkg_src/pkgcache/R/packages-gz.R:19
      4: gzfile(x, open = "r") at /Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/pkgcache/new/pkgcache.Rcheck/00_pkg_src/pkgcache/R/utils.R:32
      
      ══ testthat results  ═════════════════════════════════════════════════════════════
      OK: 282 SKIPPED: 25 FAILED: 5
      1. Error: load_primary_pkgs (@test-metadata-cache.R#177) 
      2. Error: update_replica_rds (@test-metadata-cache.R#236) 
      3. Error: read_packages_file (@test-packages-gz.R#63) 
      4. Error: packages_parse_deps (@test-packages-gz.R#71) 
      5. Error: merge_packages_data (@test-packages-gz.R#88) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# prioritizr

Version: 4.0.2

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      11: assertthat::assert_that(inherits(x, "ConservationProblem"), is.character(targets), 
             inherits(x$data$features, "data.frame"), !anyNA(targets), all(assertthat::has_name(x$data$features, 
                 targets)), length(targets) == number_of_zones(x), all(vapply(x$data$features[, 
                 targets, drop = FALSE], is.numeric, logical(1)))) at /Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/prioritizr/new/prioritizr.Rcheck/00_pkg_src/prioritizr/R/add_relative_targets.R:156
      
      ..
      ..
      ..
      ══ testthat results  ═════════════════════════════════════════════════════════════
      OK: 11532 SKIPPED: 115 FAILED: 2
      1. Error: add_absolute_targets (character, multiple zones) (@test_add_absolute_targets.R#149) 
      2. Error: add_relative_targets (character, multiple zones) (@test_add_relative_targets.R#155) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘gurobi’ ‘Rsymphony’
    ```

# qPLEXanalyzer

Version: 1.0.3

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Loading required package: ProtGenerics
    
    This is MSnbase version 2.8.3 
      Visit https://lgatto.github.io/MSnbase/ to get started.
    
    
    Attaching package: 'MSnbase'
    
    The following object is masked from 'package:stats':
    
        smooth
    
    The following object is masked from 'package:base':
    
        trimws
    
    Quitting from lines 67-71 (qPLEXanalyzer.rnw) 
    Error: processing vignette 'qPLEXanalyzer.rnw' failed with diagnostics:
    there is no package called 'gridExtra'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘qPLEXdata’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    rliPlot: no visible binding for global variable ‘logInt’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/qPLEXanalyzer/new/qPLEXanalyzer.Rcheck/00_pkg_src/qPLEXanalyzer/R/plots.R:599-621)
    rliPlot: no visible binding for global variable ‘medianLogInt’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/qPLEXanalyzer/new/qPLEXanalyzer.Rcheck/00_pkg_src/qPLEXanalyzer/R/plots.R:599-621)
    summarizeIntensities: no visible binding for global variable
      ‘Accessions’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/qPLEXanalyzer/new/qPLEXanalyzer.Rcheck/00_pkg_src/qPLEXanalyzer/R/Allfunctions.R:55-60)
    summarizeIntensities: no visible binding for global variable
      ‘Sequences’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/qPLEXanalyzer/new/qPLEXanalyzer.Rcheck/00_pkg_src/qPLEXanalyzer/R/Allfunctions.R:55-60)
    summarizeIntensities: no visible binding for global variable
      ‘Accessions’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/qPLEXanalyzer/new/qPLEXanalyzer.Rcheck/00_pkg_src/qPLEXanalyzer/R/Allfunctions.R:62-68)
    summarizeIntensities: no visible binding for global variable ‘Count’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/qPLEXanalyzer/new/qPLEXanalyzer.Rcheck/00_pkg_src/qPLEXanalyzer/R/Allfunctions.R:62-68)
    Undefined global functions or variables:
      . Accessions AveExpr B Cor CorTxt Count GeneSymbol Grouping_column
      Intensity Mean Modifications PeptideID RawIntensity RowID SampleName
      Sequence Sequences Variance X Y adj.P.Val controlLogFoldChange group
      logFC logInt logIntensity meanscaledIntensity medianLogInt
      normalizedIntensities scaledIntensity scalingFactors x xend y yend
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    'library' or 'require' call not declared from: ‘gridExtra’
    ```

# qualpalr

Version: 0.4.3

## In both

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# r511

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# raptr

Version: 0.1.3

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘gurobi’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  6.7Mb
      sub-directories of 1Mb or more:
        data   3.6Mb
        doc    1.4Mb
    ```

# RBesT

Version: 1.3-7

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.6Mb
      sub-directories of 1Mb or more:
        R      1.1Mb
        doc    1.9Mb
        libs   2.2Mb
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# rmapzen

Version: 0.4.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 31 marked UTF-8 strings
    ```

# routr

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘httpuv’ ‘utils’
      All declared Imports should be used.
    ```

# rprime

Version: 0.1.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    but_last: no visible global function definition for ‘head’
    first: no visible global function definition for ‘head’
    last: no visible global function definition for ‘tail’
    preview_frames: no visible global function definition for ‘str’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/rprime/new/rprime.Rcheck/00_pkg_src/rprime/R/preview.R:37)
    print.EprimeFrame: no visible global function definition for ‘str’
    print.FrameList: no visible global function definition for ‘str’
    Undefined global functions or variables:
      head str tail
    Consider adding
      importFrom("utils", "head", "str", "tail")
    to your NAMESPACE file.
    ```

# rrd

Version: 0.2.1

## In both

*   checking whether package ‘rrd’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/rrd/new/rrd.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘rrd’ ...
** package ‘rrd’ successfully unpacked and MD5 sums checked
** libs
ccache clang -Qunused-arguments  -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -I/usr/local/include   -fPIC  -Wall -g -O2  -c registerDynamicSymbol.c -o registerDynamicSymbol.o
ccache clang -Qunused-arguments  -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -I/usr/local/include   -fPIC  -Wall -g -O2  -c rrd.c -o rrd.o
rrd.c:1:10: fatal error: 'rrd.h' file not found
#include <rrd.h>
         ^~~~~~~
1 error generated.
make: *** [rrd.o] Error 1
ERROR: compilation failed for package ‘rrd’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/rrd/new/rrd.Rcheck/rrd’

```
### CRAN

```
* installing *source* package ‘rrd’ ...
** package ‘rrd’ successfully unpacked and MD5 sums checked
** libs
ccache clang -Qunused-arguments  -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -I/usr/local/include   -fPIC  -Wall -g -O2  -c registerDynamicSymbol.c -o registerDynamicSymbol.o
ccache clang -Qunused-arguments  -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG   -I/usr/local/include   -fPIC  -Wall -g -O2  -c rrd.c -o rrd.o
rrd.c:1:10: fatal error: 'rrd.h' file not found
#include <rrd.h>
         ^~~~~~~
1 error generated.
make: *** [rrd.o] Error 1
ERROR: compilation failed for package ‘rrd’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/rrd/old/rrd.Rcheck/rrd’

```
# rvinecopulib

Version: 0.3.0.1.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.1Mb
      sub-directories of 1Mb or more:
        include   2.5Mb
        libs      4.9Mb
    ```

# sourceR

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gtools’ ‘hashmap’ ‘reshape2’
      All declared Imports should be used.
    ```

# sparklyr

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.8Mb
      sub-directories of 1Mb or more:
        R      4.1Mb
        java   1.5Mb
    ```

# sss

Version: 0.1-0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘XML’
    ```

# testextra

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘stringi’ ‘utils’
      All declared Imports should be used.
    ```

# textreuse

Version: 0.1.4

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘tm’
    ```

# themetagenomics

Version: 0.1.0

## In both

*   R CMD check timed out
    

# tidytransit

Version: 0.3.8

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        extdata   4.4Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘here’ ‘htmltools’ ‘scales’ ‘stringr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 41 marked UTF-8 strings
    ```

# tricolore

Version: 1.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 88 marked UTF-8 strings
    ```

# trread

Version: 0.2.7

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        extdata   4.4Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘here’ ‘htmltools’ ‘scales’ ‘stringr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 41 marked UTF-8 strings
    ```

# updog

Version: 1.0.1

## In both

*   checking whether package ‘updog’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/updog/new/updog.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘updog’ ...
** package ‘updog’ successfully unpacked and MD5 sums checked
** libs
clang++ -std=gnu++11 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG  -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/updog/Rcpp/include" -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/updog/RcppArmadillo/include" -I/usr/local/include  -fopenmp -fPIC  -Wall -g -O2 -c RcppExports.cpp -o RcppExports.o
clang: error: unsupported option '-fopenmp'
make: *** [RcppExports.o] Error 1
ERROR: compilation failed for package ‘updog’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/updog/new/updog.Rcheck/updog’

```
### CRAN

```
* installing *source* package ‘updog’ ...
** package ‘updog’ successfully unpacked and MD5 sums checked
** libs
clang++ -std=gnu++11 -I"/Library/Frameworks/R.framework/Resources/include" -DNDEBUG  -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/updog/Rcpp/include" -I"/Users/hadley/Documents/devtools/assertthat/revdep/library.noindex/updog/RcppArmadillo/include" -I/usr/local/include  -fopenmp -fPIC  -Wall -g -O2 -c RcppExports.cpp -o RcppExports.o
clang: error: unsupported option '-fopenmp'
make: *** [RcppExports.o] Error 1
ERROR: compilation failed for package ‘updog’
* removing ‘/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/updog/old/updog.Rcheck/updog’

```
# wiggleplotr

Version: 1.6.1

## In both

*   checking examples ... ERROR
    ```
    ...
    Loading required package: TxDb.Hsapiens.UCSC.hg38.knownGene
    Loading required package: GenomicFeatures
    Loading required package: AnnotationDbi
    Loading required package: Biobase
    Welcome to Bioconductor
    
        Vignettes contain introductory material; view with
        'browseVignettes()'. To cite Bioconductor, see
        'citation("Biobase")', and for packages 'citation("pkgname")'.
    
    
    Attaching package: ‘AnnotationDbi’
    
    The following object is masked from ‘package:dplyr’:
    
        select
    
    > 
    > orgdb = org.Hs.eg.db
    Error: object 'org.Hs.eg.db' not found
    Execution halted
    ```

*   checking for code/documentation mismatches ... WARNING
    ```
    Codoc mismatches from documentation object 'getGenotypePalette':
    getGenotypePalette
      Code: function(old = FALSE)
      Docs: function()
      Argument names in code not in docs:
        old
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 18-28 (wiggleplotr.Rmd) 
    Error: processing vignette 'wiggleplotr.Rmd' failed with diagnostics:
    there is no package called 'EnsDb.Hsapiens.v86'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘EnsDb.Hsapiens.v86’ ‘org.Hs.eg.db’
    ```

*   checking R code for possible problems ... NOTE
    ```
    plotCoverage: no visible global function definition for ‘is’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/wiggleplotr/new/wiggleplotr.Rcheck/00_pkg_src/wiggleplotr/R/wiggleplotr.R:184)
    plotCoverage: no visible global function definition for ‘is’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/wiggleplotr/new/wiggleplotr.Rcheck/00_pkg_src/wiggleplotr/R/wiggleplotr.R:185)
    plotTranscripts: no visible global function definition for ‘is’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/wiggleplotr/new/wiggleplotr.Rcheck/00_pkg_src/wiggleplotr/R/wiggleplotr.R:33)
    plotTranscripts: no visible global function definition for ‘is’
      (/Users/hadley/Documents/devtools/assertthat/revdep/checks.noindex/wiggleplotr/new/wiggleplotr.Rcheck/00_pkg_src/wiggleplotr/R/wiggleplotr.R:34)
    Undefined global functions or variables:
      is
    Consider adding
      importFrom("methods", "is")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# wordbankr

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dbplyr’
      All declared Imports should be used.
    ```

# XKCDdata

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

# ztype

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘ggplot2’ ‘lubridate’
      All declared Imports should be used.
    ```

