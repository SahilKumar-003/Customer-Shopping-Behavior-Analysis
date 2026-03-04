# 🛍️ Customer Shopping Behavior Analysis


A complete End-to-End Data Analytics Project that analyzes customer shopping behavior using Python, MySQL, and Power BI to extract actionable business insights and build an interactive decision-making dashboard.

This project demonstrates the full analytics pipeline — from data cleaning and exploration to database querying and business intelligence visualization.

## 📊 Project Overview


Understanding customer purchasing behavior is crucial for businesses to improve marketing strategies, optimize product offerings, and enhance customer experience.

This project analyzes customer shopping data to answer important business questions such as:

Which product categories generate the highest revenue?

Which age group contributes the most to sales?

What is the distribution of customers by subscription status?

How does customer behavior vary across product categories?

The insights are presented through an interactive Power BI dashboard connected directly to a MySQL database.

## 🧰 Tech Stack

Tool	Purpose

Python	Data cleaning, preprocessing, exploratory analysis
Pandas & NumPy	Data manipulation and transformation
Matplotlib & Seaborn	Data visualization during EDA
MySQL	Structured database storage and SQL analysis
ODBC Connector	Connection between MySQL and Power BI
Power BI	Interactive dashboard and business intelligence visualization
Jupyter Notebook	Development environment for Python analysis

## ⚙️ Project Workflow


The project follows a structured data analytics pipeline:

Dataset
   ↓
Data Cleaning & Exploration (Python - Jupyter)
   ↓
Structured Data Storage (MySQL Database)
   ↓
SQL Queries for Business Analysis
   ↓
Power BI Connection via ODBC
   ↓
Interactive Business Intelligence Dashboard

## 🧹 Data Cleaning & Preprocessing


Performed using Python (Pandas) in Jupyter Notebook.

Key steps include:

Handling missing values

Removing duplicate records

Standardizing categorical data

Data type conversions

Exploratory Data Analysis (EDA)

Feature inspection and validation

This ensures the dataset is clean, reliable, and ready for analysis.

##🗄️ Database Integration (MySQL)


After preprocessing, the cleaned dataset was stored in MySQL to enable structured analysis.

Tasks performed:

Created relational tables

Imported cleaned dataset

Performed analytical SQL queries

Generated aggregated metrics for reporting

## 📈 Business Questions Answered Using SQL


Some of the key analytical questions explored:

Which product category generates the highest revenue?

Which age group contributes the most to sales?

What is the average purchase amount?

What percentage of customers are subscribers vs non-subscribers?

Which product categories have the highest sales volume?

These insights help businesses understand customer purchasing patterns.

## 📊 Power BI Dashboard


An interactive dashboard was created in Power BI using data imported from MySQL via ODBC connection.

Key Dashboard Features

## ✔ KPI Cards


Total Customers

Average Purchase Amount

Average Review Rating

## ✔ Visualizations


Revenue by Category

Sales by Category

Revenue by Age Group

Sales by Age Group

Customer Subscription Distribution

## ✔ Interactive Filters


Subscription Status

Gender

Product Category

Shipping Type

The dashboard enables dynamic exploration of customer behavior.
