# Workshop: 2022 Spring School of Finno-Ugrian Studies

University of Tartu 

## Preparation

To follow the course you will need to install two programmes on your computer. 
The precise instructions for doing this on different platforms should be 
available when you follow the links below:

- First, install [R](https://ftp.eenet.ee/pub/cran/). This is a 
  statistical computer language, and is necessary for your computer to 
  understand things written in this language (if only learning natural 
  languages was so easy!). 

- It's possible to interact with R directly, but while learning it is much 
  simpler and more convenient to use a special program called 
  [Rstudio](https://www.rstudio.com/products/rstudio/download/#download), which 
  you should install only after R itself is installed. RStudio includes lots of 
  useful things, like the *console*, where you can type in text which your 
  computer will immediately interpret as things written in the R language, a 
  *help window*, where you can get information about different R commands, an 
  interface for install and update *R packages* (collections of R commands that 
  aren't available by default), graphics viewers, and much more.

Once you're installed R and RStudio you need to install the *tidyverse* 
package. This is a big collection of R packages which are all designed to give 
a consistent interface following a consistent logic, and to produce modern and 
attractive graphics. There are several ways to install a package, but for now 
let's just use the following:

- Open RStudio and select **Tools** from the menubar, then **Install 
  Packages...**. A little dialog box will pop up:

  * Leave *Install from* as it is.
  
  * Under *Packages* type *tidyverse*
  
  * The *Install to library* item tells RStudio where to put the files 
    belonging to this new library. The default should be okay (this will be a 
    directory which all accounts on your computer can see), but there might 
    also be an option to put it in a directory which only you have access to. 
    Either option is fine. 

  * Make sure the *Install dependencies* box is checked (☑︎) so that all the 
    packages that are part of the tidyverse package will be installed as well.

The tidyverse package is big, so installing it might take some time. But once 
it's installed you only have to load it, which is much quicker.

- The course homepage also has a list of useful R cheatsheets. You can download 
  these [from 
  github](https://github.com/bedlan/tartu-spring-school-R-workshop-2022/tree/main/cheatsheets), 
  or individually:

  * [dplyr](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/dplyr.pdf)
  * [ggplot2](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/ggplot2.pdf)
  * [purrr](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/purrr.pdf)
  * [r-basics-1](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/r-basics-1.pdf)
  * [r-basics-2](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/r-basics-2.pdf)
  * [rmarkdown](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/rmarkdown.pdf)
  * [rstudio-ide](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/rstudio-ide.pdf)
  * [tidyr](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/tidyr.pdf)
  * [tidyverse](https://raw.githubusercontent.com/bedlan/tartu-spring-school-R-workshop-2022/main/cheatsheets/tidyverse.pdf)

## Programme

### Day 1 (5 April)

14:30 - 15:00 *Introduction to UraTyp* (Miina Norvik) and *course overview*
(Michael Dunn)

15:00 - 16:00 *Introduction to R*: Working with RStudio and basic R commands, 
data structures, conditional statements, ‘for’ loops, functions, and more! 
(Yingqi Jing)

16:00 - 16:30 🧁🫖 Break ☕️🍰

16.30 - 18:00 *Tidy data and the Tidyverse*, using materials from the Uralic 
Typological Database (Michael Dunn)

### Day 2 (6 April)

14.30 - 15:30 *Data clustering with Principal Components Analysis (PCA)* 
(Michael Dunn)

15:30 - 16:00 *Pairwise similarity, geographic distance, heatmaps* (Yingqi 
Jing)

16:00 - 16:30 🧁🫖 Break ☕️🍰

16.30 - 18:00 *Pairwise similarity, geographic distance, heatmaps (continued)* 
(Yingqi Jing)
