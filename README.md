# Climate Data Analysis for Nepal

## Project Overview
This project performs exploratory data analysis (EDA) on climate data for Nepal using Python. It focuses on analyzing GIS data, performing data preprocessing, and visualizing key climate patterns to better understand climate variations in the region.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Omdena-NIC-Nepal/gis-data-science-assignment-Pramod058.git
   cd gis-data-science-assignment-Pramod058
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
Or,  You can simply run the first cell in climate_eda.ipynb without explicitely running it elsewhere 


And you are good to go.

## Data Sources
The analysis utilizes GIS climate data specific to Nepal (You will find two folders for the data). Data preprocessing steps include:
- Reading and cleaning raw GIS data.
- Extracting relevant climate variables for analysis

## Visualizations and Insights
This project generates several key visualizations to explore Nepal's climate patterns:
- **Geospatial Mapping:** Displaying climate metrics using GIS visualization techniques.
- **Temperature Trends:** Visualizing historical temperature changes over time using bar graph.
- **Precipitation Distribution:** Analyzing seasonal rainfall variations bar graph.

## Key Findings
- Refer to # Exploratory Data Analysis (EDA) Insights in climate_eda.ipynb
Visualizations and Insights

- Key Findings

    From the EDA process, the following insights were gathered:

    - Temperature Trends:

        In 2020, the mean temperature was -7.58°C, while in 2050, it increased to -5.47°C, showing an overall warming trend.
    
    The maximum temperature increased from 8.14°C (2020) to 11.47°C (2050), indicating higher extremes.

    - Precipitation Patterns:

        The mean precipitation decreased from 50.84 mm in 2020 to 48.29 mm in 2050, with more extreme variations in the future.
        
        Minimum precipitation dropped to negative values in 2050, suggesting potential data inconsistencies or extreme drought conditions in some regions.
        
        These insights help in understanding climate variability and potential impacts on agriculture, water resources, and disaster management in Nepal.

## References:
- https://seaborn.pydata.org/generated/seaborn.lineplot.html
- https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.bar.html
- https://docs.qgis.org/3.40/en/docs/gentle_gis_introduction/vector_data.html
- https://guides.lib.utexas.edu/gis/documentation-guides-and-tutorials


## Author
- [Pramod Aryal]('https://www.linkedin.com/in/pramod58/')