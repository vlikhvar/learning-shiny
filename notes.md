Save app in : app.R

Lunch app : click Run App in RStudio

Create account at : shinyapps.io

devtools::install_github("rstudio/shinyapps")
library(shinyapps)

Deploy app on shinyapps.io :

library(rsconnect)
rsconnect::deployApp('.')

Slides : 
bit.ly/shiny-quickstart-1
bit.ly/shiny-quickstart-2




