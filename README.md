# FloodCamML (shinyapps.io)

This repository houses a template for a shiny web application that uses a machine learning model to classify webcam images for flooding and collect training images and labels from users. 

This template includes code for deploying the application to [**shinyapps.io**](https://shinyapps.io). This template is based off the [COPE COMET](https://copecomet.github.io/index.html) "sunny-day" flooding shiny application, the [NC12 Flood CamML](https://github.com/FloodCamML/NC12-FloodCamML). 

The published web application is: 
* built with R using {[shiny](https://github.com/rstudio/shiny)}
* writing data to Google Sheets & images to Google Drive
* hosted with [shinyapps.io](https://shinyapps.io)

## Instructions

See the [Flood CamML website](https://floodcamml.org/docs/intro) for detailed instructions. The tutorial will explain how to use this code template, set up the necessary Google APIs/permissions, and deploy the app.

## Example

An example (NC-12 Flood CamML) is available at [nc12.floodcamml.org](https://nc12.floodcamml.org/)

## Other deployment options

Code for deploying the application to [Google Cloud Run](https://cloud.google.com/run) is available in the [FloodCamML_cloudrun repo](https://github.com/FloodCamML/FloodCamML_cloudrun).

## About the CamML Project

CamML is an open source project for crowd labeling and ML prediction of real-time webcam imagery. See the full project description at [floodcamml.org](https://floodcamml.org/).
