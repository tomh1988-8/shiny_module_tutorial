library(shiny)

########## app ##############################################################
histogramApp <- function(){
  ui <- fluidPage(
    histogramUI("hist1")
  )
  server <- function(input, output, session){
    histogramServer("hist1")
  }
  shinyApp(ui, server)
}

# run the app
histogramApp()