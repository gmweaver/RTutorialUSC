
# Overview

The **RTutorialUSC** R package is a tutorial/presentation that covers
the basics for reading, manipulating, visualizing, and analyzing data in
R. Here we take a practical approach by going through the basic flow of
analyzing data in R and teach core concepts of R along the way. The
tutorial utilizes the R package **learnr** to build code examples
directly into an ioslides presentation and can be used as a teaching aid
or for self-guided learning. All R packages required to run the code in
this tutorial will be installed when you install this R package

<!-- README.md is generated from README.Rmd. Please edit that file -->

# Setup

The following instructions will setup your computer to run R, RStudio,
and enable you to install R packages from Github.

Please follow the instructions below for your OS:

**Windows**

1.  Download and install the latest version of R (3.6.1)
    [Here](https://cran.r-project.org/bin/windows/base/R-3.6.1-win.exe)
      - Note: This tutorial requires R version \> 3.5.0, if you have an
        R version older than this, please update.
2.  Download and install RStudio
    [Here](https://www.rstudio.com/products/rstudio/download/#download)
      - Note: For easiest installation select from “Installers for
        Supported Platforms”
3.  Download and install Rtools for Windows
    [Here](https://cran.r-project.org/bin/windows/Rtools/Rtools35.exe)

**Mac**

1.  Download and install the latest version of R (3.6.1)
    [Here](https://cran.r-project.org/bin/macosx/R-3.6.1.pkg)
      - Note: This tutorial requires R version \> 3.5.0, if you have an
        R version older than this, please update.
2.  Download and install RStudio
    [Here](https://www.rstudio.com/products/rstudio/download/#download)
      - Note: For easiest installation select from “Installers for
        Supported Platforms”
3.  Download and install gfortran for Mac
    [Here](https://cran.r-project.org/bin/macosx/tools/gfortran-6.1.pkg)
4.  Download and install clang for Mac
    [Here](https://cran.r-project.org/bin/macosx/tools/clang-8.0.0.pkg)

# Installing the R Package

We will go over this in-person, but if you are already comfortable with
R and Rstudio, feel free to get a head start.

1.  Open Rstudio
2.  Install the R package **devtools** by running the following command
    in the console:

<!-- end list -->

``` r
install.packages("devtools")
```

3.  Install **RTutorialUSC** R package with devtools by running the
    following command in the console:

<!-- end list -->

``` r
devtools::install_github("gmweaver/RTutorialUSC")
```

# Run the Tutorial

1.  Load the **RTutorialUSC** package by running the following command
    in the console:

<!-- end list -->

``` r
library(RTutorialUSC)
```

2.  Start the tutorial by running the following command in the console:

<!-- end list -->

``` r
learnr::run_tutorial("Introduction to R", "RTutorialUSC")
```

If a new browser window/tab opens with a presentation titled
“Introduction to R”, :tada: congrats :tada:, you are ready to start\!
