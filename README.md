# 📊 Power BI Job Market Analytics

An interactive Power BI project analyzing LinkedIn job posting data to identify trends across countries, companies, job roles, career levels, job types, and skills.

## 🎯 Project Objective

The goal of this project is to transform a large raw job-market dataset into an interactive business intelligence dashboard that helps users understand:

- Which countries have the highest job demand
- Which job roles are most in demand
- Which skills employers require most
- How career levels differ across roles
- How hiring patterns differ between countries
- Which company categories contribute most to hiring

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Star Schema
- Data Visualization

## 📂 Dataset

The project uses the **1.3M LinkedIn Jobs & Skills 2024** dataset.

The data contains more than one million LinkedIn job postings with information about:

- Companies
- Countries
- Job positions
- Job types
- Career levels
- Skills
- Job posting dates

## 🧹 Data Preparation

Power Query was used to clean and transform the raw data.

Main transformations included:

- Removing unnecessary columns
- Handling duplicate values
- Standardizing text values
- Cleaning company and country information
- Splitting job skills into individual rows
- Standardizing similar skills into common categories
- Creating dimension tables
- Preparing the data for relational modeling

## 🗂️ Data Model

A star-schema-style model was created using:

### Fact Table
- fact_job_postings

### Dimension Tables
- dim_country
- dim_company
- dim_position
- dim_job_type
- dim_job_level
- Dim_Date

### Bridge Table
- bridge_job_skills

The tables are connected using one-to-many relationships to support efficient filtering and analysis.

## 🧮 DAX Analysis

DAX measures and calculated columns were created for analysis, including:

- Total Jobs
- Total Companies
- Total Countries
- Total Positions
- Jobs per Company
- Jobs Requiring Skill
- Skill Demand %
- Company Market Share %
- Country Market Share %
- Position Market Share %
- Company Rank
- Country Rank
- Position Rank
- Dynamic Market Share %
- Job Age calculations

## 📈 Dashboard Pages

### 1. Job Market Overview
Provides an overall view of job demand, job types, career levels, countries, and daily job postings.

### 2. Country Job Market Details
A drill-through page providing detailed analysis for a selected country, including jobs, companies, skills, and roles.

### 3. Roles & Career Levels
Analyzes the most in-demand roles and compares career-level demand.

### 4. Skills Intelligence
Analyzes skill demand across countries and career levels.

### 5. Job Market Comparison
Compares hiring patterns, job types, cities, countries, and total opportunities.

### 6. Companies & Hiring
Analyzes company-category hiring and provides dynamic comparisons using field parameters.

## ⚙️ Interactive Features

The dashboard includes:

- Slicers
- Drill-through
- Page navigation
- Buttons
- Field parameters
- Dynamic measures
- Interactive filtering
- Top-N analysis
- Ranking
- Market-share analysis

## 💡 Key Skills Demonstrated

This project demonstrates practical experience in:

**Power BI | Power Query | DAX | Data Cleaning | Data Modeling | Star Schema | Data Visualization | Dashboard Design | Business Intelligence**

## 👤 Author

**Hadi Razi Hadi Al-Zubaidi**

Power BI & Data Analytics Portfolio Project
