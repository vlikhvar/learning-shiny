Rshiny Cheat Sheet
==================

Input functions()
---------------

Used for UI, for example inside fluidPage().

* actionButton
* submitButton
* checkboxInput
* checkboxGroupInput
* dateInput
* dateRangeInput
* fileInput
* numericInput
* passwordInput
* radioButtons
* selectInput
* sliderInput
* textInput

Output functions()
----------------

Used for UI, for example inside fluidPage().

* dataTableOutput : an interactive table
* htmlOutput : raw html
* imageOutput
* plotOutput
* tableOutput
* textOutput
* uiOutput : a shiny ui element
* verbatimTextOutput : literal/exact text (without formating)

Render functions()
----------------

Used for server, for example for setting the output.

* renderDataTable
* renderImage
* renderPlot
* renderPrint
* renderTable
* renderText
* renderUI

Important reactive functions
----------------------------

* render*()
* reactive()

data <- reactive({...})
data() 

* isolate() : makes non-reactive object
* observeEvent() : triggers code to run on server (ex. download data)
* observe()
* eventReactive() 
* reactiveValues()



