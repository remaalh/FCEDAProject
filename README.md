FCEDA Business Data Automation & Visualization

Improving Processing/Analysis Time on Large Datasets 
Built for the Fairfax County Economic Development Authority (FCEDA)  
George Mason University | MIS 462 PREP Project

#Team Members

- Rema Alharthi  
- Victor Luque  
- Hailey Ortega  
- Chau Phan  
- Ellie Yang  
Faculty: Dr. Brian K. Ngac  
Agency: Fairfax County Economic Development Authority

#Project Overview

Public business registration data in Virginia holds valuable insight but is messy, inconsistent, and difficult to work with. FCEDA needed a faster, scalable way to clean, enrich, and visualize this data to support outreach efforts and economic planning.

Our team developed a cloud-based ETL pipeline using AWS and an interactive Tableau dashboard to automate the transformation and visualization of business registration records.

#Problem Statement

Manual data processing was slowing down FCEDA’s ability to:
- Identify and contact newly registered office/industrial businesses
- Validate whether a business is located within Fairfax County
- Visualize trends over time and across geographies

#Our Solution

We created a serverless data pipeline and business intelligence solution:

- AWS Lambda + S3: Automates ingestion, cleaning, and geocoding of business records
- Amazon Location Service: Adds latitude and longitude using address data
- Tableau Dashboard: Enables users to filter by city, ZIP code, incorporation date, and keyword to explore business data visually
- Outpu*: Cleaned CSVs and real-time dashboard updates ready for use in Tableau, Salesforce, and ArcGIS

#Tech Stack

- AWS Lambda (Python)
- Amazon S3
- Amazon Location Service
- Tableau
- Boto3 (AWS SDK for Python)
- Pandas

#Demo

- [Watch Dashboard Walkthrough (YouTube)](link-to-video)
- Screenshots available in `dashboard/`

