# Mortality, birth, natural population growth and emigration in Portugal

## Description
The aim of this project is to to visualise and combine the following variables: mortality rate, birth rate and migration in Portugal due to my interest in Portugal’s demographic situation. Its objective is to see the decreasing natural growth rate over the years whilst considering the impact of emigration as a possible cause.
![Screenshot 2024-06-19 at 07 15 17](https://github.com/mfpa231/mortality_birth_pt/assets/107937846/7836eade-a80a-4577-be15-c57bd2a51db6)

## Interface
There are three data visualisations which can be viewed individually by clicking on each button. 
![Screenshot 2024-06-19 at 07 16 21](https://github.com/mfpa231/mortality_birth_pt/assets/107937846/1d0d0ebd-d287-44f0-8316-bb7776bf7393)



## Tools used
This data visualisation was coded using the [D3.js](https://d3js.org) library. 
It uses the [bubble plot](https://d3-graph-gallery.com/bubble.html) example as a foundation, including the [bubble legend](https://d3-graph-gallery.com/graph/bubble_legend.html) and the [tooltip](https://d3-graph-gallery.com/graph/bubble_template.html) to give information on hover.

## Data
The project uses five data sets obtained from [Pordata.pt](https://www.pordata.pt), a statistics database about Portugal and Europe, covering themes such as population, education and health. The data sets can be accessed here:

- [Emigrants per thousand habitants](https://www.pordata.pt/en/portugal/emigrants+per+thousand+inhabitants-832)
- [Crude birth rate](https://www.pordata.pt/en/portugal/crude+birth+rate-527)
- [Crude death rate](https://www.pordata.pt/en/portugal/crude+death+rate+and+infant+mortality+rate-528)
- [Permanent Immigrants]([https://www.pordata.pt/portugal/imigrantes+permanentes+total+e+por+nacionalidade-3795](https://www.pordata.pt/en/portugal/permanent+immigrants+total+and+by+nationality-3795))
- [Permanent Emigrants](https://www.pordata.pt/en/portugal/permanent+emmigrants+total+and+by+nationality-3797)

The natural population growth rate was calculated by subtracting the crude death rate from the crude birth rate.

## Acknowledgments
This project was developed as part of the assessment for the Data Visualisation course given by Professor [Isaac Pante](https://isaacpante.net) at the University of Lausanne. 
