# tartu-spring-school-R-workshop-2022
2022 Spring School of Finno-Ugrian Studies, University of Tartu 2022; Workshop 5-6 April

## Installations

- Install [R](https://cran.r-project.org/mirrors.html) and [Rstudio](https://www.rstudio.com/products/rstudio/download/#download)

- Core R packages
  ```R
  install.packages(c("tidyverse", "ggplot2", "knitr", "rmarkdown"))
  ```
  
- `Latex` and [`pandoc`](https://pandoc.org/installing.html) if you want to render the rmarkdown notebook into pdf or html. The following commands are used to install `pandoc` via homebrew on your terminal.

  ```bash
  # install homebrew
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  # install pandoc
  brew install pandoc
  ```

- Rmarkdown template

  Pls open the Rmarkdown template file (**Rmarkdown-template.Rmd**) with Rstudio, and render (click knit or **shift + cmd + k**) it on your computer. If everything goes well, you should get a pdf document in the same directory.

- Useful R cheatsheets

## Day 1
(1) Basic R commands (e.g., data structures, conditional statements, for loop & function) and Rstudio (1 h) - Yingqi

(2) Introduce UraTyp data and user-interface + ex (2 h) - Michael

- Visualization (e.g., scatterplot) & tidyverse syntax

## Day 2
(3) PCA + visualization (1 h) - Michael

(4) pairwise similarities & geographical distances and heatmaps (2h) - Yingqi

