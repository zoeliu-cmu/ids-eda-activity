# CMU Interactive Data Science
# Exploratory Data Analysis In-Class Activity

## Overview

This repository contains an interactive data science tutorial that showcases fundamental pandas operations and data analysis techniques using a real-world dataset on civil war onset indicators. The tutorial is designed as hands-on learning experience where students explore factors that might be associated with the outbreak of civil conflicts.

## Learning Objectives

By completing this tutorial, you will learn how to:

1. **Load and inspect data** from CSV files using pandas
2. **Clean and preprocess data** by handling missing values and data types
3. **Perform exploratory data analysis (EDA)** using filtering, grouping, and aggregation
4. **Engineer new features** to derive meaningful insights from raw data
5. **Interpet visualizations** using Altair
6. **Apply statistical analysis** techniques to understand patterns in data
7. **Communicate findings** effectively while considering context and limitations
8. **Work with Jupyter notebooks** for interactive data science workflows

## Dataset Description

The tutorial uses a dataset containing country-level characteristics and civil war onset indicators across multiple 5-year periods. Key variables include:

- **Economic indicators**: Export dependence, GDP growth, education levels
- **Social/demographic indicators**: Population, ethnic fractionalization, dominance
- **Conflict indicators**: Civil war onset, months of peace
- **Geographic indicators**: Population concentration

Each row represents a country during a specific 5-year interval, allowing analysis of how various factors correlate with the outbreak of civil conflicts.

## Repository Structure

```
DS_Tutorial/
├── README.md          # This file
├── requirements.txt   # Python dependencies
├── ch.csv             # Main dataset (Collier-Hoeffler Civil War Dataset)
├── Pandas_Cheat_Sheet.pdf # Reference material
├── EDA_Notebook.ipynb     # Main activity notebook
```

## Installation Instructions

### Prerequisites

- Python 3.8 or higher
- Git (for cloning the repository)

### Setup

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Create a virtual environment** (recommended):
   ```bash
   # Using conda
   conda create -n ds_tutorial python=3.9
   conda activate ds_tutorial
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Open the project in VS Code (preferred, see installation instructions below)**:
   ```bash
   code .
   ```

4. **Or Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

5. **Open the tutorial notebook**:
   Navigate to `EDA_Notebook.ipynb` and start learning!

### Alternative: Using conda

If you prefer conda for package management:

```bash
conda install pandas numpy altair matplotlib seaborn scipy jupyter scikit-learn
```

## Getting Started

1. Start with the main tutorial notebook: `EDA_Notebook.ipynb`
2. Follow along with each cell, running the code and reading the explanations
3. Complete the practice questions and exercises throughout the notebook
4. Use the `Pandas_Cheat_Sheet.pdf` as a reference for pandas operations
5. After completing the main tutorial, challenge yourself with the capstone project

## Recommended: Using Visual Studio Code

While you can use traditional Jupyter Notebook in your browser, we **highly recommend using Visual Studio Code** for the best notebook editing experience. VS Code is open-source and provides enhanced features for data science workflows:

### Setting up VS Code for Data Science

1. **Install Visual Studio Code**:
   - Download from [https://code.visualstudio.com/](https://code.visualstudio.com/)
   - Install for your operating system

2. **Install the Python extension**:
   - Open VS Code
   - Go to Extensions (Ctrl/Cmd + Shift + X)
   - Search for "Python" and install the official Microsoft Python extension
   - This automatically includes Jupyter notebook support

3. **Open the project in VS Code**:
   ```bash
   code .
   ```

4. **Select your Python interpreter**:
   - Open any `.ipynb` file
   - VS Code will prompt you to select a kernel
   - Choose the Python environment where you installed the requirements
   - If using conda: Select the `ds_tutorial` environment

### Working with Notebooks in VS Code

- **Run cells**: Click the play button or use Shift + Enter
- **Add cells**: Click the "+ Code" or "+ Markdown" buttons
- **View variables**: Use the Variables explorer in the notebook interface
- **Debug code**: Set breakpoints and use the integrated debugger
- **View dataframes**: Click on dataframe variables to see them in a table format

### Pro Tips for VS Code + Notebooks

1. **Use the Command Palette** (Ctrl/Cmd + Shift + P):
   - "Notebook: Run All Cells"
   - "Notebook: Clear All Outputs"
   - "Notebook: Restart Kernel"

2. **Keyboard shortcuts**:
   - `Shift + Enter`: Run cell and move to next
   - `Ctrl/Cmd + Enter`: Run cell and stay on current cell
   - `A`: Add cell above
   - `B`: Add cell below
   - `DD`: Delete cell

3. **Split view**: Open the CSV file alongside your notebook to reference the data structure

4. **Integrated terminal**: Access your Python environment directly within VS Code

## Troubleshooting

### Common Issues

1. **Package installation errors**: Ensure you're using Python 3.8+ and have updated pip
2. **Jupyter not starting**: Try `python -m jupyter notebook` instead of just `jupyter notebook`
3. **Missing data file**: Ensure `ch.csv` is in the same directory as the notebooks
4. **Visualization issues**: Some charts may not display properly in older browsers

### Getting Help

- Check the pandas documentation: https://pandas.pydata.org/docs/
- Altair documentation: https://altair-viz.github.io/
- For specific tutorial questions, review the explanatory text in each notebook cell
