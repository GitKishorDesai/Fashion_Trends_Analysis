# Fashion Trends Analysis

A comprehensive data visualization and analysis project focused on understanding fashion retail trends, pricing strategies, and consumer preferences in the Indian clothing market.

## Project Overview

This project analyzes a dataset from an Indian clothing retail company containing approximately 31,000 fashion items. The analysis provides insights into pricing strategies, discount patterns, brand performance, and consumer preferences across different categories of clothing and accessories.

## Dataset

The [dataset](https://www.kaggle.com/datasets/manishmathias/fashion-reliance-trends/data) was sourced from Kaggle and contains the following information:
- **Brand**: Clothing brand names
- **Description**: Product descriptions
- **Original Price**: Manufacturer's suggested retail price (MRP)
- **Discount Price**: Actual selling price
- **Category by Gender**: Men's, Women's, or Unisex items
- **Category by Attire**: Type of clothing (Topwear, Bottomwear, Footwear, etc.)
- **Category by Cloth**: Specific clothing items (Shirts, Jeans, Shoes, etc.)

## Key Features

### Interactive Web Application
- **Streamlit-based frontend** with three main sections:
  - Introduction page with project overview
  - Interactive dashboards with Tableau visualizations
  - AI-powered chatbot for data queries

### Data Analysis Capabilities
- **Discount Analysis**: Track discount percentages across brands, categories, and product types
- **Pricing Analysis**: Compare selling prices and identify pricing trends
- **Brand Performance**: Analyze brand popularity and market presence
- **Category Insights**: Understand consumer preferences across different clothing categories

### AI Chatbot
- Natural language query interface
- Converts English questions to SQL queries
- Provides real-time data insights
- Powered by Groq API with LLaMA model



## Key Insights

### Brand Performance
- **Performax** leads in total items sold
- **Swadesh** offers the highest average discounts
- **Ajio** maintains the lowest discount rates

### Category Analysis
- **Shoes** are the highest-selling category in the clothing store
- **Footwear** commands the highest average selling prices
- **Western Wear** receives the highest discounts
- **Women's clothing** outsells men's clothing

### Pricing Trends
- **Vivitka** brand has the highest average selling price
- **Frisbee** brand offers the most affordable options
- Men's clothing is slightly more expensive than women's clothing

## Technical Implementation

### Data Processing
1. **Data Cleaning**: Removed unnecessary columns and standardized formats
2. **Feature Engineering**: Created discount percentage calculations
3. **Category Extraction**: Generated new categories from product descriptions
4. **Brand Consolidation**: Grouped low-frequency brands as "Others"

### Visualization
- **Tableau Public** dashboards for interactive visualizations
- **Streamlit** for web application interface
- **SQLite** database for efficient data querying

### Dependencies
- Streamlit for web interface
- Pandas for data manipulation
- SQLite for database operations
- Tableau for advanced visualizations
- Groq API for AI chatbot functionality


### Usage
1. **Introduction**: Overview of the project and dataset
2. **Dashboards**: Explore interactive visualizations by category
3. **Chatbot**: Ask natural language questions about the data

## Data Sources

- **Original Dataset**: [Kaggle - Fashion Reliance Trends](https://www.kaggle.com/datasets/manishmathias/fashion-reliance-trends/data)
- **Processed Data**: Available as `Cleaned_Data.xlsx`
- **Database**: SQLite database with processed data

## Future Enhancements

- Real-time data updates
- Advanced machine learning models for trend prediction
- Enhanced chatbot capabilities
- Mobile-responsive design
- Additional data sources integration