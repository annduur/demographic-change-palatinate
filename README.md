# Population Change in the Palatinate

This project explores demographic change in the Palatinate (Pfalz), a region in Rhineland-Palatinate, Germany. Using municipality-level population data from 1970 to 2022, I examine which communities have grown or declined and what long-term population loss could mean for some of the region's smallest villages. 
This project was originally developed alongside a journalistic article on demographic change in rural areas.

## Research Questions

- Which municipalities have experienced the strongest population growth or decline since 1970?
- If historical population trends continued, which small villages would approach a population of zero first?
- What does population decline mean for the people who remain in these communities?

The last question adds a social perspective to the quantitative analysis. I was particularly interested in the situation of older women, who may be especially affected by declining local infrastructure and services, including public transport and accessibility.
To put the data into a broader sociological context, I also spoke with Prof. Stefan Hradil, a sociologist specializing in social structure and social inequality in Germany, about rural population decline and how communities can respond to demographic change.

## Data

The analysis uses municipality-level population data for Rhineland-Palatinate covering 1970–2022. The original data includes total population, age structure, and municipality identifiers.
For this repository, the data has been cleaned and reduced to the variables and geographic areas relevant to the analysis.
Geographic boundaries are based on open geodata from the GeoPortal Rhineland-Palatinate. The original geographic dataset was filtered and processed to include only municipalities in the Palatinate used in this project.

## Analysis

The analysis includes:

- population change between 1970 and 2022
- identification and comparison of strongly growing and shrinking municipalities
- exploratory linear trend projections for shrinking villages
- municipality-level geographic visualizations
- interactive charts and maps

The linear projections explore when a municipality would theoretically reach a population of zero if its historical linear trend continued unchanged. 
They are illustrative extrapolations rather than demographic forecasts and should not be interpreted as predictions of when a village will actually disappear!

## Tools

The project was developed in R, primarily using:

- `tidyverse` for data preparation and analysis
- `ggplot2` for data visualization
- `sf` for spatial data processing
- `plotly` for interactive visualizations

## Output

The final output is an interactive R Markdown data story combining the quantitative analysis with visualizations, maps, and the journalistic article translated to English since it was originally made in German. I apologize for the mix of German and English used. I just now translated everything to English for Github while I made the project quite some time ago :)
