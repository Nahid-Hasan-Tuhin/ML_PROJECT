# ML_PROJECT
# TITLE: Big Mart Sales Prediction using Machine Learning
# Introduction
The Big Mart Sales Prediction project aims to build a predictive model that can estimate the sales of products based on key attributes such as product type, outlet size, location, and marketing strategies. Using regression techniques like XGBoost, the project seeks to identify relationships between features and sales performance. The ultimate goal is to assist retail managers and stakeholders in making data-driven business decisions to maximize profit and efficiency.

# Dataset Description

The dataset used in this project contains detailed information about products sold at different Big Mart outlets. It consists of 5,681 records and 11 attributes, each representing product characteristics or store-related information. The data serves as the foundation for building a predictive model that estimates product sales across various stores.

# Attributes Description
The dataset (data/ml_project.csv) contains product and outlet attributes:

Item_Identifier — unique product ID

Item_Weight — weight (may have missing values)

Item_Fat_Content — low/regular (needs normalization)

Item_Visibility — product display visibility (%)

Item_Type — product category

Item_MRP — Maximum Retail Price

Outlet_Identifier — unique outlet ID

Outlet_Establishment_Year — year outlet opened

Outlet_Size — Small / Medium / Large (has missing values)

Outlet_Location_Type — Tier 1 / Tier 2 / Tier 3

Outlet_Type — Supermarket types / Grocery store

