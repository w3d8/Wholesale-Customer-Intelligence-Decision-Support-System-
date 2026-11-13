# Wholesale Customer Intelligence Decision Support System

A data-driven Decision Support System (DSS) designed to analyze wholesale customer purchasing behavior, prioritize high-value customers, and support data-driven sales decisions using a Greedy Heuristic Algorithm.

## Project Overview
This project analyzes the Wholesale Customers dataset to identify and prioritize high-value customers based on their historical annual spending across six product categories.

The system applies a Greedy Heuristic Algorithm to rank customers and select priority customers under different sales-visit capacity scenarios.

## Project Objectives
- Analyze customer purchasing patterns across six product categories.
- Identify customers with the highest historical spending.
- Rank customers based on their total annual spending.
- Select priority customers under different sales-visit capacity scenarios (K = 5, 10, and 20).
- Support sales resource allocation and customer prioritization.

## Methodology
The project follows a data-driven analytical approach:
Data Loading and Preparation: Load and process the wholesale customer dataset using Python and Pandas.
Customer Analysis: Examine customer spending across the six product categories.
Customer Prioritization: Apply a Greedy Heuristic Algorithm to rank customers based on their total spending.
Decision Support: Evaluate customer selection under different visit-capacity scenarios.

## Dataset
The project uses the Wholesale Customers dataset, which contains customer spending records across six product categories:
- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen
  
The dataset is stored in the data/ directory.

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- Greedy Heuristic Algorithm
- Data Analysis
- Decision Support Systems

## Project Structure
```
wholesale-customer-intelligence-dss/
│
├── README.md
├── Wholesale_Customer_Intelligence_DSS_Final.ipynb
│
└── data/
    └── Wholesale customers data.csv
```

## How to Run
- 1.Clone or download this repository.
- 2.Make sure the dataset is placed inside the data/ folder.
- 3.Open the Jupyter Notebook.
- 4.Run the notebook cells sequentially to execute the analysis and customer prioritization model.

## Expected Outcome
The system generates a ranked list of high-value customers and supports sales prioritization by identifying customers with the highest combined historical spending under different visit-capacity constraints.
