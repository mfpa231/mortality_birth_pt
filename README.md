# Mortality, birth, natural population growth and emigration in Portugal

## Description
The aim of this project is to show a link between the mortality rate and birth rate in Portugal during the years 1960-2022, adding a third dimension, emigration and a fourth dimension, natural growth rate. Its objective is to see the decreasing natural growth rate over the years whilst considering the impact of emigration as a possible cause.
![Screenshot 2024-06-05 at 22 40 44](https://github.com/mfpa231/mortality_birth_pt/assets/107937846/b16d6b85-c9ff-469b-907c-79322a8e11c9)

## Tools used
This data visualisation was coded using the [D3.js](https://d3js.org) library. 
It uses the [bubble plot](https://d3-graph-gallery.com/bubble.html) example as a foundation, including the [bubble legend](https://d3-graph-gallery.com/graph/bubble_legend.html) and the [tooltip](https://d3-graph-gallery.com/graph/bubble_template.html) to give information on hover.

## Data
The project uses three data sets obtained from [Pordata.pt](https://www.pordata.pt), a statistics database about Portugal and Europe, covering themes such as population, education and health. The three data sets can be accessed here:

- [Emigrants per thousand habitants](https://www.pordata.pt/en/portugal/emigrants+per+thousand+inhabitants-832)
- [Crude birth rate](https://www.pordata.pt/en/portugal/crude+birth+rate-527)
- [Crude death rate](https://www.pordata.pt/en/portugal/crude+death+rate+and+infant+mortality+rate-528)

The natural population growth rate was calculated by subtracting the crude death rate from the crude birth rate.

## Interface
The data visualisation is a bubble graph with the mortality rate (%) on the x axis, the birth rate (%) on the y axis, the size of the bubbles is based on the of number of emigrants per thousand inhabitants in that year and the colour of the bubble ranges from red to blue based on the natural growth rate (the lower the rate, the closer to blue on the scale). 
There is a key on the right-hand side to give the user an idea of the relation between the size and percentage of the bubbles as well as the colour gradient.![Screenshot 2024-06-05 at 22 35 15](https://github.com/mfpa231/mortality_birth_pt/assets/107937846/65b2a4ee-a007-4019-b0c1-f6746971ce9b)

To get the full information the user can hover on each bubble to know the exact mortality rate, birth rate, natural growth rate and emigration rate. 

![Screenshot 2024-06-05 at 22 35 38](https://github.com/mfpa231/mortality_birth_pt/assets/107937846/ab53ee6d-510d-4b44-b660-6217b86c0324)

## Use
There is an animation which begins once the user selects 'Play'. The animation can be paused when 'Pause' is selected and then be continued as well as restarted once it has ended.
![Screenshot 2024-06-05 at 22 41 08](https://github.com/mfpa231/mortality_birth_pt/assets/107937846/8b483206-4682-4a07-84a7-70a662a68475)


## Acknowledgments
This project was developed as part of the assessment for the Data Visualisation course given by Professor [Isaac Pante](https://isaacpante.net) at the University of Lausanne. 
