# Medical Data Visualization

This project is part of the **Data Analysis with Python** certificate program. It demonstrates how to process and visualize medical examination data using Python. The primary objectives are to create a categorical plot and a heatmap to explore relationships in the dataset, particularly in the context of cardiovascular disease.

## Project Overview

- **Categorical Plot**: Visualizes the distribution of various health-related variables, separated by the presence of cardiovascular disease.
- **Heatmap**: Displays the correlation between different features in the dataset after removing outliers.

## Dataset

The dataset used in this project is `medical_examinations.csv`, which contains information from medical examinations such as height, weight, cholesterol levels, and glucose levels.

## Libraries Used

The following Python libraries are required to run this project:

- `pandas`: For data manipulation and analysis.
- `seaborn`: For data visualization.
- `matplotlib`: For creating static, animated, and interactive visualizations.
- `numpy`: For numerical computing.

## How to Run

### 1. Install the necessary libraries

Before running the code, ensure you have installed the required Python libraries. You can install them using pip:

```bash
pip install pandas seaborn matplotlib numpy
```

### 2. Clone the repository

Clone this repository to your local machine using:

bash

Copier le code

`git clone https://github.com/aymen-hadj-mebarek/Medical-Data-Visualizer.git`

### 3. Load and run the Jupyter Notebook

Open the Jupyter Notebook (`Medical_Data_Visualization.ipynb`) in Jupyter or JupyterLab and run the cells sequentially.

### 4. View the Results

The notebook will generate two key visualizations:

- `catplot.png`: A categorical plot showing the distribution of various health-related variables.
- `heatmap.png`: A heatmap showing the correlation between features in the dataset.

### 5. Running in Command Line (Optional)

If you prefer to run the script directly from the command line, you can execute the following:

bash

Copier le code

`jupyter nbconvert --to script Medical_Data_Visualization.ipynb python Medical_Data_Visualization.py`

## Project Structure

- `Medical_Data_Visualization.ipynb`: The main Jupyter Notebook containing the code and explanations.
- `medical_examinations.csv`: The dataset used for analysis.
- `catplot.png`: The output image of the categorical plot.
- `heatmap.png`: The output image of the heatmap.

**Note**: This project is completed as part of the **Data Analysis with Python** certification program. The goal is to apply data analysis and visualization techniques to a real-world dataset, showcasing skills in Python programming, data manipulation, and visualization.