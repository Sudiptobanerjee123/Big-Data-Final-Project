# Chicago Crime Analysis and Prediction

## Overview

This project analyzes crime data from Chicago to identify trends in criminal activity and predict future crime incidents. We use machine learning models like K-Nearest Neighbors (KNN) and Random Forest to analyze and predict crime locations based on historical data.

## Dataset

The dataset used is the Chicago Police Department's crime data from 2001 to 2021, containing over 6 million reported criminal incidents. It includes information such as:

- **Date and Time**
- **Primary Type of Crime**
- **Location Description**
- **Arrest Status**
- **Geographic Coordinates**
- **Community Area**

## Objectives

- Identify temporal and spatial trends in crime occurrences
- Build predictive models (KNN and Random Forest) to forecast crime occurrences
- Explore relationships between crime type, time of day, and location

## Tools and Libraries Used

- **Python**
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **Folium** and **GeoPandas** for geospatial analysis
- **Scikit-learn** for machine learning models

## Data Preprocessing

- Handling missing values using KNN imputation
- Feature engineering (e.g., extracting time-based features)
- Normalizing/scaling features
- Encoding categorical variables

## Exploratory Data Analysis (EDA)

### Temporal Analysis
- Crime trends over years
- Crime distribution by month, day of the week, and hour

### Spatial Analysis
- Crime location density heatmap
- Neighborhood crime distribution
- Crime clusters using KMeans

### Correlation Analysis
- Correlation matrix of numerical variables
- Crime type correlations
- Time and location relationships

## Predictive Modeling

### K-Nearest Neighbors (KNN)
- Used for predicting crime locations
- Achieved **72% accuracy** in predicting crime locations

### Random Forest
- Used for predicting crime types and locations
- Achieved **83% accuracy**, outperforming KNN
- Identified key predictors: hour of day, crime type, and neighborhood

## Results

| Model           | Accuracy |
|------------------|----------|
| KNN              | 72%      |
| Random Forest    | 83%      |

### Key Findings
- Random Forest outperformed KNN in predicting crime locations and types.
- Temporal patterns identified, such as peak crime hours and seasonal trends.
- Geospatial analysis revealed variations in crime density across neighborhoods.
- Environmental correlations noted, with peak crime rates during summer months and evening hours.

## Challenges Faced

- Data quality issues and imbalanced dataset
- Model overfitting
- Computational resource limitations
- Geospatial processing challenges

## Future Work

- Incorporate additional external data (weather, economic indicators)
- Explore deep learning models (CNN, LSTM) for complex pattern recognition
- Develop a real-time crime prediction system
- Optimize models for larger datasets and real-time streams

## Contributors

- Sudipto Banerjee

## Acknowledgments

- Chicago Police Department for providing the crime data
- Professor Joseph Rosen for guidance and feedback
- Illinois Institute of Technology for resources and support

## Citations
[1] [README.md](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/31976576/59be17e4-b9bf-4722-afd2-948c50170700/README.md)  
[2] [Report Draft](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/31976576/d8d619bd-af6c-4642-aca1-9de43e88bb85/report-draft-1.pdf)
