### My project

For my project, I will analyze birth records from the year 1991 for the state of Kansas.

To analyze the data, you will need to install the `R` package `tidyverse`. The required package can be installed using R commands.

`install.packages("tidyverse")`

### Execute the analysis

The raw birth record data is located in the project folder (`birth.Rdata`). The R Markdown script cleans the data and includes a brief description of the project and analysis results.

To execute the analysis, from the project folder you can run

`Rscript -e "rmarkdown::render('report.Rmd')"`

This will create a file called `report.html` output in your directory that contains the results.
