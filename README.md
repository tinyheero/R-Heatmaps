# Generating Heatmaps in R Workshop

This is the Github repository for the event - https://github.com/minisciencegirl/studyGroup/issues/47. The official event details are as follows:

* Date: September 8, 2015
* Time: 5:30pm
* Room: BCCA (Dorothy Lam Room)

# Preparation for the Workshop

The workshop will contain parts where you can run R code to generate some heatmaps. If you are interested in doing this, please bring your laptop to the workshop and do the following preparation steps:

1. [git](https://git-scm.com/) clone this repository:

    ```
    git clone git@github.com:tinyheero/R-Heatmaps.git
    ```
    
    The repository comes with the following files/folders:
    
    * Generating-Heatmaps-in-R.pdf: This is the PDF version of the slidedeck for the workshop.
    * Generating-Heatmaps-in-R.pptx: This is the powerpoint version of the slidedeck for the workshop.
    * heatmap-cluster.Rmd: This is a Rmarkdown file that contains a tutorial and code on how to generate the images shown in the slide deck
    * data: Folder containing the data files required for the `heatmap-cluster.Rmd` file.

2. Install [Rstudio](https://www.rstudio.com/) (if you haven't already).
3. Inside of Rstudio, make sure you install the following R packages:

    * [dplyr](https://cran.r-project.org/web/packages/dplyr/index.html)
    * [knitr](https://cran.r-project.org/web/packages/knitr/index.html)
    * [d3heatmap](https://cran.r-project.org/web/packages/d3heatmap/index.html)
    * [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html)
    * [reshape2](https://cran.r-project.org/web/packages/reshape2/index.html)
    * [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html)

4. Make sure you can render the `heatmap-cluster.Rmd` file by opening the `heatmap-cluster.Rmd` file in RStudio and then pressing the "Knit HTML" button. If it works, then you should see a separate open window open with a document titled "Generating Heatmaps in R".

# Contact

Feel free to contact me for help regarding the content in this workshop:

* email: fongchunchan@gmail.com
* twitter: [https://twitter.com/fongchunchan](https://twitter.com/fongchunchan)
* blog: [http://tinyheero.github.io/](http://tinyheero.github.io/)
