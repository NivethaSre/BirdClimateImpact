# Predicting the Impact of Climate Change on Bird Populations

## 1. Tracking a Changing Climate
The climate is changing around the world. The impacts of climate change are particularly noticeable in their effects on birds. Many bird species are moving north, if they can, to stay in climatic conditions that are suitable for them.

This project analyzes data from the [UK Met Office](https://www.metoffice.gov.uk/climate/uk/data/ukcp09) and records from the [Global Biodiversity Information Facility (GBIF)](https://www.gbif.org/) to build a species distribution model using machine learning. Our model predicts where a specific bird species is likely to occur in the future, which is valuable for conservation efforts.

In this notebook, we focus on modeling the Scottish crossbill (*Loxia scotica*), a small bird native to Scotland that inhabits coniferous forests.

## 2. Dataset
- **Climate Data**: Collected from the UK Met Office, containing temperature, precipitation, and other environmental variables.
- **Bird Population Data**: Sourced from GBIF, containing species occurrence records with geospatial information.
- **GIS Data**: Used to map and visualize changes in habitat distribution over time.

## 3. Methodology
1. **Data Preprocessing**:
   - Cleaning missing values
   - Normalizing climate variables
   - Merging datasets for analysis
2. **Exploratory Data Analysis (EDA)**:
   - Heatmaps and correlation matrices
   - Distribution plots of bird occurrences over time
3. **Machine Learning Models**:
   - **Time-Series Analysis**:
     - ARIMA and Prophet models to analyze population trends.
   - **Deep Learning**:
     - LSTMs for long-term predictions of bird distributions.
   - **Species Distribution Modeling**:
     - Random Forest and XGBoost for habitat suitability analysis.
4. **Visualization**:
   - GIS mapping of bird migrations.
   - Heatmaps showing climate-bird relationships.

## 4. Results and Insights
- **Predicted migration patterns**: The model indicates a northward shift in bird populations due to rising temperatures.
- **Correlation with climate variables**: A strong relationship between precipitation, temperature, and species distribution.
- **Conservation recommendations**: Areas that need habitat protection based on future predictions.

## 5. How to Run
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn geopandas prophet statsmodels tensorflow
   ```
2. Download datasets from the UK Met Office and GBIF.
3. Run the Jupyter Notebook step by step.

## 6. Future Work
- Improve deep learning models for better accuracy.
- Integrate real-time climate data for continuous updates.
- Expand analysis to multiple bird species across regions.

## 7. References
- UK Met Office Climate Data
- GBIF Species Records
- Various machine learning libraries used

