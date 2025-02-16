# London-Bike-Ride-Analysis

## Introduction
This project analyzes London bike sharing data to uncover usage patterns and the impact of weather conditions on bike rides. Using Python and Tableau, dynamic visualizations provide insights into bike usage trends, helping to optimize bike sharing services.

## Data Source
The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset), includes detailed records of bike rides in London. Key attributes include timestamps, temperature, humidity, wind speed, and weather conditions. This comprehensive dataset allows for in-depth analysis of temporal and environmental impacts on bike ride frequency.

## Technologies Used
- **Python**: Used for data manipulation and cleaning with the Pandas library.
- **Tableau**: Employed to create dynamic and interactive visualizations.
- **Kaggle API**: For programmatically downloading the dataset.

## Files in the Repository
This repository contains several key files that contribute to the project's functionality:
- **LondonBikeRideAnalysis.twbx**: The Tableau dashboard file showcasing the visual analysis of the London bike sharing data.
- **London_Bikes_Data.ipynb**: A Jupyter notebook containing the Python code used for data cleaning and preparation.
- **london_bikes_cleaned.xlsx**: The cleaned Excel file output from the Python script, ready for visualization.
- **london_merged.csv**: The original dataset downloaded from Kaggle, used as the basis for the analysis.

## Features of the Dashboard
The Tableau dashboard includes several interactive features:
- **Total Bike Rides**: Visualizes the total number of rides.
- **Moving Average Chart**: Shows trends over time with adjustable parameters.
- **Temperature vs. Wind Speed Heat Map**: Analyzes environmental factors affecting bike usage.
- **Interactive Tooltips**: Provide additional data on bike rides by weather and hour.

View the interactive dashboard [here](https://public.tableau.com/views/LondonBikeRideAnalysis_17389822968590/Dashboard).

```html
<div class='tableauPlaceholder' id='viz1739745350453' style='position: relative'>
<noscript><a href='#'><img alt='Dashboard ' src='https://public.tableau.com/static/images/Lo/LondonBikeRideAnalysis_17389822968590/Dashboard/1_rss.png' style='border: none' /></a></noscript>
<object class='tableauViz'  style='display:none;'>
<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
<param name='embed_code_version' value='3' /> 
<param name='site_root' value='' />
<param name='name' value='LondonBikeRideAnalysis_17389822968590/Dashboard' />
<param name='tabs' value='no' />
<param name='toolbar' value='yes' />
<param name='static_image' value='https://public.tableau.com/static/images/Lo/LondonBikeRideAnalysis_17389822968590/Dashboard/1.png' /> 
<param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />
<param name='display_spinner' value='yes' />
<param name='display_overlay' value='yes' />
<param name='display_count' value='yes' />
<param name='language' value='en-GB' />
</object>
</div>
<script type='text/javascript'>
var divElement = document.getElementById('viz1739745350453');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} 
else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} 
else { vizElement.style.width='100%';vizElement.style.height='1127px';}                     
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
