# Workshop on parallel processing in R
Taught by Ritika Giri Fall Quarter of 2023 Northwestern University's Research Computing and Data Services


# Getting Started
* Download the materials to your machine by clicking on the green "Code" button on the top right and selecting "Download ZIP".
* Unzip the downloaded folder, and double-click on the .RProj file to open up the R Project in RStudio.
* Open `nsir-parallel-processing.qmd` and work through the materials.


# Concepts

* Serial vs Parallel processing
* What is a core, processor, node and cluster
* Using `mclapply` from the `{parallel}` package
* Running loops in parallel with `{foreach}` and `{doParallel}`
* Practical examples of boot-strapping for 95% confidence intervals in parallel

# Components

* README.md markdown file outlining the repository
* .Rproj folder maintaining an R Project for this directory
* nsir-parallel-processing.qmd Quarto document with the workshop contents

# Required Installs
* R and RStudio
* Packages: `foreach` and `doParallel`