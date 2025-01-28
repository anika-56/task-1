# task-1
# Epidemic Spread Analysis using SIR Model
## Files

-   `task_1 (1).ipynb`: Jupyter Notebook containing the Python code for the analysis.
-   `dataset/data.csv`: The dataset in CSV format.
-   `output_with_changes.csv`: The dataset in CSV format with added columns for calculated daily changes.
-   `README.md`: This file, providing a summary of the project.## Analysis and Findings
## Analysis and Findings
### 1. Data Loading and Cleaning
-  The dataset consists of 4 columns - Day, Susceptible, Infected and Recovered individuals.
- The dataset consists of numerical data and has no missing values

### 2. Data Manipulation
- The daily change in susceptible, infected and recovered individuals are calculated by taking the difference with respect to the previous day
-The percentage of susceptible, infected and recovered individuals for each day are also calculated.

### 3. Basic Analysis
- The analysis reveals the peak of the infection was around 8th day, with 200 infected individuals
- The total percentage of the population that became infected during the outbreak was around 191.4%

### 4. Data Visualization

-   **Line Chart:** Shows that as the number of Infected individuals increases sharply, the number of susceptible individuals decrease, and later the recovered individuals increase and the system is stable with a significant number of recovered and low susceptible.

-   **Bar Chart:** Illustrates that the daily change in the number of infected individuals is initially positive, indicating the spread, reaches a peak, and then becomes negative as more people recover.

-   **Pie Chart:** Presents the final distribution as:
    -   47.6% of the population remained susceptible.
    -   0.0% of the population remained infected.
    -   52.4% of the population recovered.

## Libraries Used

-   `pandas`: For data manipulation and analysis.
-   `numpy`: For numerical operations.
-   `matplotlib`: For data visualization.
