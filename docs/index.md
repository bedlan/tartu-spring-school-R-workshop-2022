<!-- Published at: https://bedlan.github.io/tartu-spring-school-R-workshop-2022/ -->

You can find this page using the link: [https://bit.ly/rworktartu](https://bit.ly/rworktartu)

## Data files

The following links will let you download selections of the Uratyp and Uralex 
data for offline usage.

 - [Uratyp 
   values](https://raw.githubusercontent.com/cldf-datasets/uratyp/v1.1/cldf/values.csv) 
 - [Uratyp 
   languages](https://raw.githubusercontent.com/cldf-datasets/uratyp/v1.1/cldf/languages.csv)
 - [Uratyp 
   parameters](https://raw.githubusercontent.com/cldf-datasets/uratyp/v1.1/cldf/parameters.csv)
   
   The paths to the downloadable version of these files are "https://raw.githubusercontent.com/cldf-datasets/uratyp/v1.1/cldf/values.csv" etc.
   
 - [Uralex 
   data](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/data/uralex.tsv)

If you want to use the data directly in R from its online home you can copy and paste the following:

```{r}
values <- read_csv("https://raw.githubusercontent.com/cldf-datasets/uratyp/v1.1/cldf/values.csv") 
languages <- read_csv("https://raw.githubusercontent.com/cldf-datasets/uratyp/v1.1/cldf/languages.csv")
parameters <- read_csv("https://raw.githubusercontent.com/cldf-datasets/uratyp/v1.1/cldf/parameters.csv")
lexdata <- read_csv("https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/data/uralex.tsv")
```

## Cheat sheets

Some background on using RStudio:

  * [rstudio-ide](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/rstudio-ide.pdf)
 
Useful one- or two-page documents explaining the usage of some important R 
packages:

  * [dplyr](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/dplyr.pdf)
  * [ggplot2](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/ggplot2.pdf)
  * [purrr](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/purrr.pdf)
  * [r-basics-1](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/r-basics-1.pdf)
  * [r-basics-2](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/r-basics-2.pdf)
  * [rmarkdown](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/rmarkdown.pdf)
  * [tidyr](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/tidyr.pdf)
  * [tidyverse](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/tidyverse.pdf)

