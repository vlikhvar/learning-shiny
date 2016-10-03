Save app in : app.R

Lunch app : click Run App in RStudio

Create account at : shinyapps.io

devtools::install_github("rstudio/shinyapps")
library(shinyapps)

No need to install for: RStudio IDE v. 0.99 or >

Deploy app on shinyapps.io :

library(rsconnect)
rsconnect::deployApp('.')

Slides : bit.ly/shiny-quickstart-1

