# intro to R workshop materials
This repository is compilations for resources for R classes on November 2018, at Dhulikhel Hospital. We would like to thank all the R community without which it won't be possible to compile these materials. 

This will Contains 
- R Code 
- Data for Practice 
- Presentation

# Software and Files

## R and RStudio Installation Instructions

This workshop assumes you have recent versions of R and RStudio. If you don't have R and RStudio Install from following links 

### For Windows 
R: https://cran.r-project.org/bin/windows/base/ 

R Studio: https://download1.rstudio.org/RStudio-1.1.463.exe

### For Mac
R: https://cran.r-project.org/bin/macosx/R-3.5.1.pkg

R Studio: https://download1.rstudio.org/RStudio-1.1.463.dmg

### For Linux (ubuntu)
R 
```ubuntu
# R with OpenBLAS
sudo apt-get install r-base
```
RStudio 

```ubuntu
# R with OpenBLAS
sudo apt-get install libopenblas-base r-base
```

## Workshop Materials

How to get the materials depends on how you plan to access R and RStudio for the workshop.

### On your laptop 

If you installed R and RStudio on your laptop, download all of the materials to your laptop.  Click on the green Clone or Download button above, then download the repository as a ZIP file.  

![github download](images/githubdownload.png)

Find the downloaded .zip file on your computer, likely in your Downloads folder.  Unzip it - usually by double-clicking.  This will create a directory.  Move this somewhere on your computer where you'll be able to find it, like your Documents folder.  

You should open the file `r_intro_nov2018.Rproj` in this folder to open the materials as an RStudio project.  Double-click on it from your Finder/File Explorer, or from RStudio, File menu > Open Project..., then navigate to the location of the file.

### using RStudio Cloud

If you're using RStudio Cloud, go to https://rstudio.cloud and log in (or create an account if needed).  Click on Your Workspace in the left Menu.  Then make sure you are on the Projects tab, and click down arrow in the blue button for New Project.  Choose the option of New Project from a Git Repo.  The repo address is https://github.com/prabinrs/introR_Nov2018.  

![rstudio cloud new project](images/rstudiocloud.png)

This will copy all of the files from this repository into your new project.  This will take a few moments to copy files from this repository.  You'll then need to install packages.  Open `packagelist.r` and run the code.  The tidyverse package will take a while to install.  

You can use this space like you would your RStudio on own computer, except you can only access the files that are part of the project and save files within the project.

## Types of Files

The main materials are slides.  Keynote and Powerpoint versions are available:

* Google Slide will be shared once complete. 

Exercises we do during the workshop are either in the slides or in .R files in the [exercises directory](/exercises).

Reference materials and independent practice exercises are written in RMarkdown (*.Rmd).  You can open these files directly in RStudio and run the code chunks.  The RMarkdown files have also been converted to html files for easy viewing.  Exercise files have one RMarkdown file (with answers) and two html files (one with and one without answers).  Links to the html files are in the [coreexercises directory](/coreexercises).

## Opening/Downloading Files

RMarkdown files can be previewed in GitHub, but they won't include the output of the code cells.  HTML files generated from the RMarkdown generally can't be previewed directly in the GitHub repository view, but they can be viewed online through GitHub Pages; links are provided for that where relevant.  HTML files are self-contained; this means they are on the large side, but they can be downloaded and viewed locally as a single file.

REMEMBER: if downloading individual files from GitHub, you want to download the RAW version of a file.  Otherwise, it's often better to download everything together by using the green clone/download button for the entire repository.

## Other Resources


The handouts for this workshop are from:

[R Reference Card](https://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf): lists many commonly used functions

[RStudio Base R Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2016/05/base-r.pdf): syntax reference

[Population Health Data Science with R] (https://bookdown.org/medepi/phds/) : Open Book by Tomás J. Aragón

Online reference for plotting for this workshop:

[Base R Examples](https://dcgerard.github.io/stat234/base_r_cheatsheet.html) by David Gerard

[R Base Graphics Cheat Sheet](http://publish.illinois.edu/johnrgallagher/files/2015/10/BaseGraphicsCheatsheet.pdf) by Joyce Robbins

