---
title: "Data and R Package"
---
The book *The Riddle of Literary Quality* presents a synthesis of research findings from the project The Riddle of Literary Quality. That project brought together a lot of data: the opinions on 401 books of almost 14,000 participants in The National Reader Survey (2013) and all kinds of data on those 401 books. More about The Riddle of Literary Quality can be found on the [project website](https://literaryquality.huygens.knaw.nl/), which also collects all the [publications](https://literaryquality.huygens.knaw.nl/?page_id=588) that came out of it.

The data used by Karina van Dalen-Oskam for the book *The Riddle of Literary Quality* have been made available, insofar as they may be shared, in two ways: in csv files and in the litRiddle package for R. An exception to this are the research data underlying Andreas van Cranenburgh's work, as described in Chapter 6. Those can be found at [Andreas van Cranenburgh's website](https://andreasvc.github.io/).

The csv files and a description of what they contain can be found in the [RiddleData repository in Github](https://github.com/karinavdo/RiddleData). The litRiddle R package and all necessary information about it are stored in the [LitRiddle Data repository in Github](https://github.com/karinavdo/LitRiddleData).

R is a free software environment in which statistical analyses can be done and their results visualised in graphs. R can be downloaded from the [R website](https://www.r-project.org/). Once R is installed, you can then load the desired R package. More on data, package and how to use it below.

**The litRiddle package for R**

The new version of the *litRiddle* package for R will be available soon on CRAN (The Comprehensive R Archive Network). The package can be installed in R with 

- install.packages("litRiddle")<br>

It may then be loaded with

- library(litRiddle)

More information about the package can then be found with

- vignette("litRiddle")

The litRiddle package was developed by Maciej Eder, Joris van Zundert, Saskia Lensink and Karina van Dalen-Oskam. How to quote the package can be found in the vignette and on Github.



