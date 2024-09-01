# eMBLEM Data Analysis

This repository contains a Jupyter notebook that analyzes the agreement between eMBLEM, a method under development, and AH, the ground truth standard. The notebook includes exploratory data analysis, an interactive Bland-Altman plot, linear regression, and reference chart generation.

## Contents
- `emblem-data-analysis-clean.ipynb`: The main Jupyter notebook.
- `data/`: Directory containing sample data files.
- `images/`: Directory containing images used in the notebook (if applicable).

## How to Use

1. **Clone the repository**:
   - Clone this repository to your local machine using the following command:
     ```bash
     git clone https://github.com/your-username/emblem-data-analysis.git
     ```

2. **Install the required Python packages**:
   - You can install the required packages by running the following command in your terminal:
     ```bash
     pip install -r requirements.txt
     ```
   - Alternatively, you can manually install the necessary packages using pip:
     ```bash
     pip install pandas numpy matplotlib scipy scikit-learn pillow ipywidgets
     ```

3. **Open the Jupyter notebook**:
   - Navigate to the cloned repository directory and start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `emblem-data-analysis-clean.ipynb` in the Jupyter interface.

4. **Run the cells**:
   - Run all cells in the notebook to perform the analysis. Make sure the sample data file is in the correct directory (`data/wing_fold_data_sample.xlsx`).

## Summary
The notebook demonstrates the use of Python for data analysis and visualization in the context of comparing two measurement methods. It includes an interactive Bland-Altman plot to dynamically explore the agreement between methods.
