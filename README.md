# Mortality, birth, natural population growth and emigration in Portugal

## Description
The aim of this project is to show a link between the mortality rate and birth rate in Portugal during the years 1960-2022, adding a third dimension, emigration and a fourth dimension, natural growth rate. Its objective is to see the decreasing natural growth rate, considering the impact of emigration.

![Screenshot 2024-06-05 at 14 11 04](https://github.com/mfpa231/mortality_birth_pt/assets/107937846/5b354d92-7c6d-4597-94f1-f5050d0dc2f0)

## Tools used
This data visualisation was coded using the D3.js library. 

## Data
The project uses three data sets obtained from Pordata.pt, a statistics database about Portugal and Europe, covering themes such as population, education and health. The three data sets can be accessed here:

- [Emigrants per thousand habitants] (https://www.pordata.pt/en/portugal/emigrants+per+thousand+inhabitants-832)
- [Crude birth rate] (https://www.pordata.pt/en/portugal/crude+birth+rate-527)
- [Crude death rate] (https://www.pordata.pt/en/portugal/crude+death+rate+and+infant+mortality+rate-528)

The natural population growth rate was calculated by subtracting the crude death rate from the crude birth rate.

## Interface
The data visualisation is a bubble graph with the mortality rate (%) on the x axis, the birth rate (%) on the y axis, the size of the bubbles is based on the of number of emigrants per thousand inhabitants in that year and the colour of the bubble ranges from red to blue based on the natural growth rate (the lower the rate, the closer to blue on the scale). 
There is a key on the right-hand side to give the user an idea of the relation between the size and percentage of the bubbles as well as the colour gradient.
To get the full information the user can hover on each bubble to know the exact mortality rate, birth rate, natural growth rate and emigration rate.

## Use
There is an animation which begins once the user selects 'Play'. The animation can be paused when 'Pause' is selected and then be continued.
