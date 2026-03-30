
# Week4Project1
# Smart City Monitoring System - Team1 Galaxy

MODULE 3: Project Details – Smart City Monitoring System
Now it is time to turn theory into practice. Below are the technical details of the project. This project is designed in the Microsoft Fabric environment.

3.1 Scenario
An energy company notices that energy prices are lower on windy and sunny days. By analyzing weather, air quality, and energy prices, the company wants to predict the most eco‑friendly and cheapest time to use energy.

3.2 Technologies Used
Data Ingestion: Data Factory (Pipeline) – Collects data from APIs and stores it in the Bronze layer.

Data Processing: Spark Notebooks (Python) – Cleans and transforms the data.

Storage: OneLake (Data Lakehouse)

3.3 Data Pipeline Flow
Step 1: Data Ingestion (Bronze Layer)
Using the APIs listed below, you are expected to collect weather, air quality, and energy price data for the last 7 days (based on the pipeline run date). The data must be stored in raw JSON format in the correct layer of your architecture.

Location Information
City: Amsterdam

Latitude: 52.3676

Longitude: 4.9041
