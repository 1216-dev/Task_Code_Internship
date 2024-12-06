# Task_Code_Internship
This repository contains solutions to research internship tasks based on the paper Efficient Trading with Price Impact. The tasks involve implementing financial trading models, optimizing strategies, and experimenting with deep learning techniques to analyze trading data.

# Efficient Trading with Price Impact - Research Internship Tasks

This repository contains the solutions for the research internship tasks based on the paper *Efficient Trading with Price Impact*. The tasks involve implementing various financial models, optimizing trading strategies, and experimenting with deep learning approaches.

## Description

### Objective

To replicate and implement models and strategies described in the paper, using provided data, and generate relevant visualizations.

### Tasks

1. **Linear and Nonlinear Models**  
   - Construct and code the Linear OW Model and Nonlinear AFS Model.  
   - Visualize the distribution of price impact based on given data.

2. **Optimal Strategy with Linear Impact**  
   - Implement and code the optimal strategy as described in Section 6.2.  
   - Generate and analyze Sharpe Ratio plots.

3. **Deep Learning Algorithm for Discrete Settings**  
   - Implement the deep learning algorithm detailed in Appendix C.2.  
   - Visualize the training loss for different network structures.

## Contents

- `Task1_Question1.ipynb` - Implementation of Linear OW and Nonlinear AFS models.
- `Task1_Question2.ipynb` - Optimal strategy implementation with linear impact.
- `Task1_Question3.ipynb` - Deep learning algorithm implementation for discrete settings.
- `Trial_Tasks.pdf` - Task descriptions and reference materials.

## Data

The dataset (`merged_data.csv`) combines MBO and MBP-1 data fields. The key columns include:

- `bid_fill`: Size of filled bid orders.  
- `ask_fill`: Size of filled ask orders.  
- `signed_volume`: Difference between `bid_fill` and `ask_fill`.  
- `best_bid`: Highest bid price.  
- `best_ask`: Lowest ask price.

For more details on the dataset, visit the [Databento documentation](https://databento.com/docs/schemas-and-data-formats/mbo#fields-mbo?historical=python&live=python&reference=python).

## Usage

### Cloning the Repository

Clone the repository to your local machine:
Running the Code
Open the Jupyter Notebooks (.ipynb files) in the repository.
Execute the cells to replicate the results and visualizations.
Dependencies
Programming Languages: Python 3.8+
Libraries: numpy, pandas, matplotlib, tensorflow, keras
Additional tools like R or MATLAB may be needed if specified in the task.

Results
Price Impact Distribution
Visualizations for the Linear OW and Nonlinear AFS models.
Sharpe Ratio Plots
Analysis for optimal trading strategies.
Training Loss Curves
Results from deep learning models with different network structures.
Acknowledgments
Paper: Efficient Trading with Price Impact
Data Source: Databento
License
This repository is for educational and research purposes. Contact the repository owner for any reuse or collaboration.

Contact
For questions or collaboration, reach out:

Name: Devshree Jadeja
Email: devshreehjadeja@gmail.com
Phone: +1 934-255-9120
```bash
git clone https://github.com/yourusername/efficient-trading-tasks.git
cd efficient-trading-tasks
