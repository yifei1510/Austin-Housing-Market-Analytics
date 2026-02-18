# Austin Housing Market Analytics: Data Modelling & Performance Optimization in Power Query

## Executive Summary

This project focuses on transforming a raw real estate dataset into a structured, scalable, and high-performance business intelligence model using Power BI and Power Query.

The original dataset contained over 15,000 property records with highly repetitive attributes, inconsistent formats, and large unstructured text fields. To improve data quality and analytical reliability, the data was systematically cleaned, grouped, and de-duplicated by consolidating similar records into well-defined dimension tables.

Key transformations included standardizing data formats, grouping categorical variables, eliminating duplicate attribute combinations, and normalizing repetitive fields through surrogate keys. Multiple dimension tables were created to separate features, school metrics, property characteristics, and location data from transactional records.

In addition, unstructured text descriptions were restructured into a tokenized dimension, enabling keyword-level analysis while significantly reducing storage overhead.

As a result, the optimized data model reduced redundancy, improved query performance, and decreased file size by approximately 40%, supporting scalable multi-dimensional analysis and long-term system maintainability.

## Business Problem

The original housing dataset contained:

    High levels of repetitive attributes
    Large unstructured text fields
    Inefficient flat-table structure
    Limited scalability for future growth

Directly visualizing this data led to:

    Slower report performance
    Increased storage requirements
    Difficulty in maintaining relationships
    Limited insight from text descriptions

Without proper modeling, the dataset was unsuitable for enterprise-level analytics.

The main challenge was to convert this raw dataset into a reliable, efficient, and scalable BI model.

## Methodology

### Data Preparation

    Created layered architecture: Source → Clean → Fact → Dimension
    Standardized text formats and data types
    Optimized numeric precision
    Converted Boolean fields to user-friendly values

### Data Modeling

  Built a star schema with:
  
      Housing Fact Table
      Feature Dimension
      School Dimension
      Property Dimension
      Location Dimension
  
  Generated surrogate keys using index columns
  
  Implemented SQL-style multi-column joins in Power Query

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
