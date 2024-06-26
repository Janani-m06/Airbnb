
# Airbnb Analysis



![Logo](https://www.digital.ink/wp-content/uploads/airbnb_logo_detail.jpg)



## Domain



```http
Travel Industry, Property Management and Tourism 
```




## Tech Stack



 Python scripting, 

Data Preprocessing,

 Visualization,


EDA, 

Streamlit, 

MongoDb, 

PowerBI 

## Libraries Required

- pymongo
- pandas
- plotly.express
- matplotlib.pyplot
- seaborn

## Problem Statement:

This project aims to analyze Airbnb data using MongoDB Atlas, perform data cleaning and preparation, develop interactive geospatial visualizations, and create dynamic plots to gain insights into pricing variations, availability patterns, and location-based trends.
## Objectives

1.Establish a MongoDB connection, retrieve the Airbnb dataset, and ensure efficient data retrieval for analysis.

2.Clean and prepare the dataset, addressing missing values, duplicates, and data type conversions for accurate analysis.

3.Develop a Streamlit web application with interactive maps showcasing the distribution of Airbnb listings, allowing users to explore prices, ratings, and other relevant factors.

4.Conduct price analysis and visualization, exploring variations based on location, property type, and seasons using dynamic plots and charts.

5.Analyze availability patterns across seasons, visualizing occupancy rates and demand fluctuations using suitable visualizations.

6.Investigate location-based insights by extracting and visualizing data for specific regions or neighborhoods.

7.Create interactive visualizations that enable users to filter and drill down into the data.

8.Build a comprehensive dashboard using  Power BI, combining various visualizations to present key insights from the analysis.
## Data

Sign up for a `MongoDB Atlas` MongoDB Atlas account by visiting the MongoDB Atlas website and follow the registration process to set up your account and create a new project.


`Set Up a Cluster` 

Within your MongoDB Atlas project, set up a cluster. Choose the cloud provider and region for hosting your data, configure the cluster specifications, and create the cluster. This will serve as the database environment for storing the sample data.

`Load the Airbnb Sample Data` 

Once your cluster is set up, access the MongoDB Atlas dashboard. In the left-hand navigation menu, click on "Database Access" to create a database user with appropriate permissions for accessing and loading data. Then, select "Network Access" to set up IP whitelisting or configure other security measures.

`Import Sample Data` 

From the MongoDB Atlas dashboard, navigate to the "Clusters" page and click on your cluster. In the cluster view, select the "Collections" tab and click on the "Sample Data" button. Choose the "Load Sample Dataset" option, and MongoDB Atlas will import the Airbnb sample data into your cluster. The sample data typically includes collections for listings, reviews, and users.



## Approach


`1. MongoDB Connection and Data Retrieval`

Establish a connection to the MongoDB Atlas database and retrieve the Airbnb dataset. Perform queries and data retrieval operations to extract the necessary information for your analysis.


`2. Data Cleaning and Preparation`

Clean the Airbnb dataset by handling missing values, removing duplicates, and transforming data types as necessary. Prepare the dataset for EDA and visualization tasks, ensuring data integrity and consistency.


`3. Geospatial Visualization`

Develop a Streamlit web application that utilizes the geospatial data from the Airbnb dataset to create interactive maps. Visualize the distribution of listings across different locations, allowing users to explore prices, ratings, and other relevant factors.

`4. Price Analysis and Visualization`

Use the cleaned data to analyze and visualize how prices vary across different locations, property types, and seasons. Create dynamic plots and charts that enable users to explore price trends, outliers, and correlations with other variables.



`5. Availability Analysis by Season`

Investigate how the price of listings varies across different locations. Use MongoDB queries and data aggregation techniques to extract relevant information for specific regions or neighborhoods. Visualize these insights on interactive maps or create dashboards in tools like  Power BI.


`6. Location-Based Insights`
Develop dynamic and interactive visualizations that allow users to filter and drill down into the data based on their preferences. Enable users to interact with the visualizations to explore specific regions, property types, or time periods of interest.


`7. Interactive Visualizations`

 Power BI is used to create a comprehensive dashboard that presents key insights from your analysis. Combine different visualizations, such as maps, charts, and tables, to provide a holistic view of the Airbnb dataset and its patterns.


`8. Dashboard Creation`

 Power BI is used to create a comprehensive dashboard that presents key insights from your analysis. Combine different visualizations, such as maps, charts, and tables, to provide a holistic view of the Airbnb dataset and its patterns.

## PowerBi Report

<img width="580" alt="airbnb_report" src="https://github.com/Janani-m06/Airbnb/assets/156600141/759cc284-ff15-4bec-bc66-738c83dc03dd">





