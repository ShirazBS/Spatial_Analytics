# Spatial Analytics EasySteps

This code contains everything you need to recreate the `EasySteps` tool. The tool is an R Shiny app that can be run directly from RStudio. 

The packages needed for installation are written in the markdown file, and access to OpenStreetMap is set up. The only additional part needed to do by users is set their own working directory in the first code chunk, and create an access token for MapBox API which can be created here: (https://www.mapbox.com/).

Once the access token has been created, simply paste it in where the code asks. The code has already been created to stay well within the free tier restrictions of MapBoxAPI. 

You can view an example of how the `EasySteps` tool works below. 

[Watch the video](EasySteps_Example.mov)

## Technical Pipeline

The project was conducted in the desktop version of R (4.3.1) in RStudio (2023.06.2+561) (R Core Team, 2022), on a MacBook Pro ‘13 (2020, 2 GHz Intel i5, 16GB of RAM, macOS Sequoia 15.1). 

### Setup
First of all make sure to clone this repository to your device. 
```
git clone https://github.com/ShirazBS/Spatial_Analytics.git
```
Then simply make sure to install the packages needed based on the list provided in the script, change your working directory, and add in your own MapBoxAPI token.

For any questions regarding reproducibility please contact the author at: 202207251@post.au.dk
