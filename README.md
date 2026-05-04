# AI-Based-Supply-Chain-Automation

## Overview
This project presents an end-to-end automated data pipeline designed to streamline supply chain data processing and analysis. It eliminates manual data handling by integrating email-based data ingestion, database storage, and AI-driven analytics into a unified workflow.

The system automatically extracts data from emails, processes and stores it in a structured format, and generates key insights using AI-powered tools.

## Objective
- Reduce manual effort in data collection and preprocessing  
- Automate supply chain data workflows  
- Ensure data consistency and reliability  
- Enable real-time analytics and decision-making  

## System Architecture

The pipeline consists of the following components:

### 1. Email-Based Data Ingestion
- Monitors incoming emails based on predefined subjects (e.g., daily sales, dispatch data)  
- Automatically extracts CSV attachments  

### 2. Data Processing & Transformation
- Parses CSV data  
- Cleans and standardizes fields such as:
  - Order ID  
  - Customer ID  
  - Order Date  
  - Delivery Metrics  

### 3. Database Storage
- Stores structured data in a centralized database  
- Uses PostgreSQL via Supabase  
- Supports scalable and reliable data management  

### 4. AI-Powered Analysis
- Connects database to Quadratic AI Sheet  
- Performs analysis using AI-assisted queries and formulas  
- Generates KPIs and insights  

## Key Features
- Fully automated end-to-end pipeline  
- Email-triggered data extraction  
- Data cleaning and transformation  
- Centralized database storage  
- AI-driven analytics  
- KPI generation and visualization  

## Key Metrics (KPIs)
- On-Time Delivery Rate  
- Order Fulfillment Rate  
- Delivery Trends  
- Operational Performance Metrics  

## Tech Stack
- Workflow Automation: n8n  
- Database: Supabase (PostgreSQL)  
- AI Analysis: Quadratic AI Sheets  
- Data Format: CSV  

## Workflow
1. Email received with relevant subject  
2. n8n triggers workflow  
3. CSV attachment extracted  
4. Data cleaned and transformed  
5. Data inserted into PostgreSQL (Supabase)  
6. Data connected to Quadratic  
7. KPIs calculated and insights generated  

## Use Cases
- Supply chain performance monitoring  
- Automated reporting systems  
- Logistics data analysis  
- Real-time decision support  

## Challenges Faced
- Lack of reliable logistics datasets  
- Inconsistent KPI generation from raw data  
- Data formatting and standardization issues  

## Solution Approach
- Used structured supply chain datasets for consistency  
- Built automated pipeline for reliable data flow  
- Implemented AI-based analysis for meaningful insights  

## Outcome
- Reduced manual data handling significantly  
- Improved data accuracy and consistency  
- Enabled faster and better decision-making  
- Demonstrated real-world application of AI in supply chain analytics  

## Future Improvements
- Real-time dashboard integration (Power BI / Tableau)  
- Advanced predictive analytics  
- Integration with ERP systems  
- Alerting system for anomalies  

## Author
Sayudh  
Supply Chain Data Analyst Intern  
