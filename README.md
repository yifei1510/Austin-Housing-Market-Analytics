# Austin Housing Market Analytics: Excel, Power Query, Data Modelling and Dashboard Reporting Project

## Executive Summary

This project demonstrates my ability to use Excel Power Query to clean, transform and restructure messy raw housing data into a reporting-ready analytical model. Starting from a flat housing dataset, I standardised fields, reduced duplication, created linked tables, and built Excel Pivot Table analysis and dashboard reporting outputs.

The final model was designed to support clearer analysis of property prices, home types, bedroom distribution, living area, and school rating impact. In addition to data cleaning and modelling, I developed KPI summaries, Pivot Tables and charts to present business-facing insights in a clear and user-friendly format.

## Business Problem

The original housing dataset was stored in a flat raw format, which made analysis less efficient due to:

    repeated attributes across many records
    
    inconsistent field structures
    
    large unstructured description text
    
    limited reporting readiness for trend analysis and summary reporting

The objective of this project was to transform the raw dataset into a more structured Excel-based analytical model that could support:

cleaner reporting outputs

easier comparison across cities and home types

pricing and property trend analysis

more efficient use of Pivot Tables and charts

## Methodology

### Data Preparation

    Created layered architecture: Source → Clean → Fact → Dimension
    Standardized text formats and data types
    Optimized numeric precision
    Converted Boolean fields to user-friendly values

### Data Modeling

  Built a data model using EXCEL power pivot:
  
      Housing Fact Table
      Feature Dimension
      School Dimension
      House Dimension
      Location Dimension
      Description Dimension

<img width="494" height="379" alt="image" src="https://github.com/user-attachments/assets/2fb90711-6c83-4490-81b2-fba446058a2b" />



<img width="956" height="384" alt="image" src="https://github.com/user-attachments/assets/d0a463a1-5408-46b2-b300-5ddb579af70a" />





  ### Text Transformation

      Tokenized property descriptions into individual words
      Unpivoted multi-column text structures
      Removed punctuation, numbers, and stop words
      Normalized casing and filtered low-value tokens
      Created a structured description dimension

### Performance Optimization

    Eliminated redundant attribute storage
    Removed long text fields from fact tables
    Normalized categorical attributes
    Reduced overall model complexity

# Skills

### Technical Skills

    Power BI
    Power Query (M Language)
    Dimensional Modeling
    Star Schema Design
    Data Cleaning & Transformation
    Text Tokenization

### Analytical Skills

    Data Normalization
    Performance Optimization
    Exploratory Data Analysis
    Business Intelligence Design
    Data Quality Management

 ### Business Skills

    Analytical Problem Solving
    Insight Communication
    Model Scalability Planning

  ##  Results & Business Recommendation

  ### Key Results

  | Metric         | Before      | After                |
| -------------- | ----------- | -------------------- |
| File Size      | ~5.3 MB     | ~2.9 MB              |
| Reduction      | —           | ~40%                 |
| Data Structure | Flat Table  | Star Schema          |
| Text Data      | Raw Strings | Structured Dimension |

### Data report

<img width="667" height="373" alt="image" src="https://github.com/user-attachments/assets/f5e89e96-33cd-4d36-a33b-7488b5eeab0d" />






### Achievements

    Reduced report size by ~40%
    Improved refresh and query speed
    Built scalable dimensional architecture
    Enabled keyword-level text analysis
    Enhanced model maintainability

### Business Recommendations

    Apply dimensional modeling early in BI projects
    Separate unstructured text from fact tables
    Normalize repetitive attributes
    Optimize data types and precision
    Design for scalability from the beginning

These practices improve system reliability and reduce long-term maintenance costs.

## Next Steps

Future improvements include:

    Integrating Python-based NLP for deeper text analysis
    Building predictive pricing models
    Automating refresh pipelines
    Deploying reports to Power BI Service
    Implementing monitoring and alert systems

These enhancements would further increase analytical value and operational efficiency.
