# Dashboard Adventure Works
Business Intelligence Dashboard created from the udemy course Microsoft Power BI for Business Intelligence.

## Project Overview
This is a dashboard of a sample company that I used to learn Business Intelligence with Power BI.

## Results
#### Executive Summary
![Executive Summary](https://github.com/frantzalexander/Dashboard-Adventureworks/assets/128331579/2cd28127-81a3-459f-84ac-00cd6a4c633e)

#### Sales Trending
![Sales Trending](https://github.com/frantzalexander/Dashboard-Adventureworks/assets/128331579/e93c745d-31f4-449b-8a1e-88fe23250aa3)

#### Product Details
![Product Details](https://github.com/frantzalexander/Dashboard-Adventureworks/assets/128331579/580ff7e2-09ee-4a4f-8255-b57d1170e732)

## Process
```mermaid
flowchart TD
start(((START)))
import[Import: Data and Lookup Tables]
check[Check Data Formatting]
clean[Clean Data]
calendar[Create Rolling Calendar]
data_model[Create Data Model]
schema[Create Snowflake Schema]
measures[Create Calculated Measures]
visuals[Create Visualizations]
finish(((END)))
start --> import
import --> check
check --> clean
clean --> calendar
calendar --> data_model
data_model --> schema
schema --> measures
measures --> visuals
visuals --> finish
