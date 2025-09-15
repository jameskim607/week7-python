# Iris Dataset Analysis

## Project Overview
This project is a Python-based data analysis and visualization assignment. It demonstrates the process of loading, exploring, and visualizing the classic Iris dataset using the `pandas` and `matplotlib` libraries. The work is contained within a Jupyter Notebook and provides a clear example of fundamental data analysis techniques.

## Objectives
The primary objectives of this assignment were to:
- Load and explore a dataset's structure and integrity.
- Perform basic statistical analysis and grouping operations.
- Create insightful and customized visualizations to uncover patterns in the data.
- Document the process and findings in a reproducible manner.

## Dataset Description

### Iris Dataset
- **Source:** `sklearn.datasets.load_iris()`
- **Description:** A classic dataset in pattern recognition and machine learning, containing measurements of 150 iris flowers from three species.
- **Features (Numerical):**
  - `sepal length (cm)`
  - `sepal width (cm)`
  - `petal length (cm)`
  - `petal width (cm)`
- **Target Variable (Categorical):** `species` (setosa, versicolor, virginica)

## Project Structure
The project consists of a single, self-contained Jupyter Notebook:

## Code and Libraries
The analysis was performed using the following Python libraries:
- **pandas:** For data manipulation and analysis.
- **matplotlib:** For creating static, animated, and interactive visualizations.
- **seaborn:** To provide a high-level interface for drawing attractive statistical graphics.
- **scikit-learn:** To easily access the Iris dataset.

## Key Steps and Workflow

### 1. Data Loading and Exploration
- The dataset was loaded from `sklearn.datasets` into a pandas DataFrame.
- The `.head()`, `.info()`, and `.describe()` methods were used for initial inspection.
- Data integrity was confirmed using `.isnull().sum()` (no missing values were found).

### 2. Data Analysis
- Basic statistics (mean, median, standard deviation, etc.) were computed for all numerical columns.
- Data was grouped by the `species` categorical variable to analyze differences between groups.
- Key findings were extracted from the statistical summaries.

### 3. Data Visualization
The following four required visualizations were created to illustrate findings:
- **Line Chart:** Showing the values of sepal length across the first 30 samples.
- **Bar Chart:** Comparing the average sepal length for each iris species.
- **Histogram:** Displaying the distribution of petal lengths across all samples.
- **Scatter Plot:** Exploring the relationship between sepal length and petal length, colored by species.

## How to Run the Project
1.  **Prerequisites:** Ensure you have Python installed along with Jupyter Notebook and the required libraries:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn jupyter
    ```
2.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
3.  **Open the Notebook:** In the browser window that opens, navigate to and click on `week8.ipynb`.
4.  **Run the Code:** Execute the cells sequentially from top to bottom (`Cell` -> `Run All`).

## Findings and Insights

-   **Clear Species Distinction:** The **setosa** species is easily distinguishable by its significantly smaller petal and sepal measurements.
-   **Size Gradient:** A clear size gradient exists from setosa (smallest) to versicolor (medium) to virginica (largest).
-   **Strong Correlation:** The scatter plot reveals a strong positive relationship between sepal length and petal length.
-   **Effective for Classification:** The strong clustering in the scatter plots confirms that these measurements are highly effective for classifying the iris species.

## Conclusion
This project successfully demonstrates the full workflow of a basic data analysis task, from ingestion to visualization. It highlights the power of Python's data science stack for extracting meaningful insights from a well-structured dataset and serves as a perfect example of exploratory data analysis (EDA).

---
*This project was completed as an assignment for data analysis and visualization.*