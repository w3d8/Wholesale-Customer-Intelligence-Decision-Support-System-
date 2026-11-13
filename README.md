# Wholesale Customer Intelligence Decision Support System

A data-driven Decision Support System (DSS) designed to analyze wholesale customer purchasing behavior, prioritize customers, and support data-driven sales decisions using a Greedy Heuristic Algorithm.
Project Overview
This project analyzes the Wholesale Customers dataset to identify and prioritize high-value customers based on their historical annual spending across six product categories.
The system applies a Greedy Heuristic Algorithm to rank customers and select priority customers under different sales-visit capacity scenarios.
Objectives
• Analyze customer purchasing patterns across six product categories.
• Identify customers with the highest historical spending.
• Rank customers based on their total annual spending.
• Select priority customers under different sales-visit capacity scenarios (K = 5, 10, and 20).
• Support sales resource allocation and customer prioritization.
Methodology
The project follows a data-driven analytical approach:
1. Data Loading and Preparation: Load and process the wholesale customer dataset using Python and Pandas.
2. Customer Analysis: Examine customer spending across the six product categories.
3. Customer Prioritization: Apply a Greedy Heuristic Algorithm to rank customers based on their total spending.
4. Decision Support: Evaluate customer selection under different visit-capacity scenarios.
Dataset
The project uses the Wholesale Customers dataset, which contains customer spending records across six product categories:
• Fresh
• Milk
• Grocery
• Frozen
• Detergents_Paper
• Delicassen
The dataset is located in the data/ directory.
Tools & Technologies
• Python
• Jupyter Notebook
• Pandas
• Greedy Heuristic Algorithm
• Data Analysis and Decision Support Systems
Project Structure
wholesale-customer-intelligence-dss/
│
├── README.md
├── Wholesale_Customer_Intelligence_DSS_Final.ipynb
│
└── data/
    └── Wholesale customers data.csv
How to Run
1. Clone or download this repository.
2. Ensure the dataset is placed inside the data/ folder.
3. Open the Jupyter Notebook.
4. Run the notebook cells sequentially to execute the analysis and customer prioritization model.
Expected Outcome
The system provides a ranked list of high-value customers and supports sales prioritization decisions by identifying customers with the highest combined historical spending under different visit-capacity constraints.
