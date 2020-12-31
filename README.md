

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.*. The required libraries to be imported are embedded into the code. Further packages to be installed are geopy and folium.

## Project Motivation<a name="motivation"></a>

For this project, I was interested in combining the demografics from the city of Munich, Germany, with the venues information from the Foursquare API and geodata from public.opendatasoft.com to identify the most attractive neighbourhoods for an imaginary new food delivery service.
The focus of the analysis are following parameters:

1. Population density
2. Employment data
3. Restaurant density
4. Population to Restaurant ratio

which are used to compute following indicators:

1. Net Employement rate: for the assessment of high-demand neighborhoods; it should be above the city average
2. Population Density: higher density of employed population is used to assess high demand
3. Restaurant density: higher density of restaurants is used to assess high supply
4. Population_Restaurant_Ratio: used as control parameter to ensure that the demand doesn't exceed too much the supply

## File Descriptions <a name="files"></a>

There is a Python notebook including comments that summarizes the analysis performed as well as a report describing the data used, the methodology and the results:
https://github.com/lisfon/IBM_Data_Science_Certificate/blob/main/Capstone_Project_Notebook.ipynb

## Results<a name="results"></a>

The main findings of the code can be found in the repository:
https://github.com/lisfon/IBM_Data_Science_Certificate/blob/main/Capstone_Project_Report.ipynb

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit for the data used goes to the Open Data Portal of the city of Munich, Foursquare API and Opendatasoft.

