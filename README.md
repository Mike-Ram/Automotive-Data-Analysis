# Automobile Selection Analysis: Matching Vehicle Characteristics to Lifestyle Needs

## Table of Contents
* [Project overview](#project-overview)
* [Objectives](#objectives)
* [Data Source](#data-source)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Visual Analysis](#visual-analysis)
* [Key Findings](#key-findings)
* [Tools and Technologies](#tools-and-technologies)
* [Recommendations](#recommendations)

## Project Overview
This analysis identifies optimal automobile body styles based on individual lifestyle requirements and financial considerations. By examining relationships between performance metrics, pricing, and fuel efficiency, the project provides actionable insights for informed vehicle selection.

## Objectives
* Analyze the relationship between horsepower, price, and fuel efficiency
* Identify cost variations across different automobile body styles
* Evaluate fuel efficiency patterns across vehicle categories
* Provide data-driven recommendations for vehicle selection based on usage patterns and budget constraints

## Data Source
Automobile Data: The primary dataset used for this analysis is the "Automobile_dataset.csv", containing detailed information each car body by the company.
  
## Data Preparation
The dataset was sourced from Kaggle and required minimal preprocessing due to its clean structure. No significant data cleaning or transformation was necessary for this analysis.

## Exploratory Data Analysis
The analysis focused on answering these key questions:

1.**Price-Horsepower Relationship:** How does horsepower correlate with vehicle pricing?

2.**Fuel Efficiency Analysis:** What are the efficiency patterns across different body styles?

3.**Body Style Pricing:** Which automobile body styles command premium pricing?

4.**Performance-Efficiency Tradeoff:** What is the relationship between city MPG and horsepower?

## Visual Analysis

<img width="989" height="590" alt="2PriceVSHorse" src="https://github.com/user-attachments/assets/3db3dd27-13fd-4e02-873d-8f8d67877b90" />
Figure 1: Positive correlation between horsepower and vehicle price
<br></br>
<br></br>

<img width="989" height="590" alt="2FuelEfficiency" src="https://github.com/user-attachments/assets/d276d0cb-b0d0-49aa-8464-94be6eb547b3" />
Figure 2: Fuel efficiency comparison across vehicle categories
<br></br>
<br></br>

<img width="989" height="590" alt="2BodyStyle" src="https://github.com/user-attachments/assets/45d34a9b-e298-44ca-a38b-c93b35594c25" />
Figure 3:  Price variations by automobile body style
<br></br>
<br></br>

<img width="995" height="590" alt="2HorsepowerVSMPG" src="https://github.com/user-attachments/assets/9e3bb4ed-eef2-4fdf-8951-3480f0daeab3" />
Figure 4: Tradeoff between engine power and fuel efficiency
<br></br>
<br></br>

## Key Findings
* Strong positive correlation exists between horsepower and vehicle price

* Hardtop body styles generally command premium pricing but exhibit lower fuel efficiency

* Sedans, hatchbacks, and wagons offer optimal balance of affordability and fuel efficiency

* Inverse relationship observed between horsepower and fuel efficiency (MPG)

* Higher-priced vehicles tend to prioritize performance over fuel economy

## Tools and Technologies
 * **Python:** Primary programming language

* **Pandas:** Data manipulation and analysis

* **Matplotlib & Seaborn:** Data visualization

## Recommendations
### For Budget-Conscious Consumers
* **Avoid hardtop body styles** if operating with moderate budgets due to higher costs and lower fuel efficiency

* **Prioritize sedan, hatchback, or wagon models** for optimal balance of affordability and fuel economy

### For High-Usage Scenarios
* **Select higher-efficiency vehicles** for intensive daily use, as they provide greater travel distance per fuel unit

* **Consider the performance-efficiency tradeoff:** Higher horsepower typically reduces fuel efficiency, impacting operating costs

### General Guidance
* Evaluate total cost of ownership, considering both purchase price and long-term fuel expenses

* Align vehicle selection with actual usage patterns rather than aspirational preferences

* Use the identified efficiency patterns to make informed decisions based on individual priorities (performance vs. economy)
