## ggplot2 visualisation

An adaptation of Cedric Scherer's tutorial [https://cedricscherer.netlify.app/2019/05/17/the-evolution-of-a-ggplot-ep.-1/](https://cedricscherer.netlify.app/2019/05/17/the-evolution-of-a-ggplot-ep.-1/), by Paula Andrea Martinez. 
Updates: Data cleaned and ready to download.
Simple modifications to the plot. 

*Last updated Nov 10, 2020*

### Recommended structure
It is recommended that you use and RProject.
In which you need at least three folders
- rmarkdown
- plots
- data

### Creat a new Rmarkdown file
Save the Markdown file in the rmarkdown folder

### Libraries required

If you haven't installed the libraries yet, first install them
```{r}
install.packages(tidyverse)
install.packages(here)
```

If libraries are installed, load them
```{r}
library(tidyverse)
library(here)
```

### data
- [See the data](https://github.com/orchid00/visualisationsCS/blob/master/data/df_sorted.csv) on GitHub.
- [Download the data](https://raw.githubusercontent.com/orchid00/visualisationsCS/master/data/df_sorted.csv) (Right click, Save Link As...) save it in the data folder

### Materials
- [download visualisations.Rmd](https://orchid00.github.io/visualisationsCS/visualisations.Rmd) save it in the rmarkdown folder
- [see the code](https://orchid00.github.io/visualisationsCS/visualisations)

### This site
[https://orchid00.github.io/visualisationsCS/](https://orchid00.github.io/visualisationsCS/)

### This repo
[https://github.com/orchid00/visualisationsCS](https://github.com/orchid00/visualisationsCS)
