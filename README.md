# New-York-Taxi-Demand-Prediction

![image](https://github.com/princebari/New-York-Taxi-Demand-Prediction/assets/115543070/eb702426-0bb1-4366-9e79-404ddb754bc1)

<h2> Introduction </h2>
Medallion (yellow) cabs are concentrated in the borough of Manhattan but can be hailed anywhere throughout the five boroughs of New York City with a raised hand or from a taxi stand. In the New York city, people use taxis at a much higher frequency than most places. Instead of booking customers by phone ahead of time, there is still a majority of New York taxi drivers that pick-up passengers on street. 

The New York City Taxi Demand Prediction project aims to develop accurate predictive models to forecast taxi demand across various areas of the city. By leveraging historical taxi trip data and employing machine learning algorithms, the project uncovers insights into the temporal and spatial patterns of taxi demand. This information is invaluable for taxi service providers, city planners, and transportation authorities to make informed decisions and optimize resource allocation. This repository provides a comprehensive solution for taxi demand prediction, including data preprocessing, exploratory data analysis (EDA), model training, evaluation.

<h2> About Dataset </h2>
The project utilizes the TLC Trip Record data provided by the New York City Taxi and Limousine Commission (TLC). This dataset contains detailed information about taxi trips, including pickup and drop-off locations, timestamps, and other relevant attributes. The dataset is publicly available and can be downloaded from the New York City TLC website https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page.

<h2>Business Problem</h2>
The business problem of this project is to accurately predict taxi demand in different areas of New York City. Overall, accurate taxi demand prediction addresses the business problem of optimizing taxi services, enhancing service quality, reducing costs, improving traffic management, and aiding in urban planning for the benefit of taxi companies, customers, and city authorities.

<h2>ML Problem Formulation</h2>

*    Time-series forecasting and Regression

*    To find number of pickups, given location cordinates(latitude and longitude) and time, in the query reigion and surrounding regions.
     
*    To solve the above we would be using data collected in Jan - Mar 2015 to predict the pickups in Jan - Mar 2016.

<h2>Performance metrics</h2>

*   Mean Absolute percentage error.

*   Mean Squared error.

<h2> Machine Learning Objective </h2>
The machine learning objective of this problem is to develop models that can accurately predict the number of taxi pickups given specific cluster or region in New York City, and  10-minute time intervals.
