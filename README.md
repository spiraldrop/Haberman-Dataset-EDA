# Haberman-Dataset-EDA

In this Jupyter Notebook project, I conducted an exploratory data analysis (EDA) on the Haberman Dataset. The primary objective was to gain insights into the dataset, understand its characteristics, and perform data visualization to identify patterns and trends.

## Dataset Overview

The dataset contains information about patients who underwent surgery for breast cancer at the University of Chicago's Billings Hospital. The dataset includes the following columns:
- `age`: Age of the patient
- `year`: Year of the operation
- `positive_nodes`: Number of positive axillary nodes detected
- `survival_status`: Survival status (1: patient survived more than 5 years, 2: patient died within 5 years)

The dataset comprises 306 entries, and the data types of the columns are integers.

## Tasks Completed

1. **Data Cleaning and Renaming**: I started by reading the dataset into a Pandas DataFrame. I renamed the columns for clarity.

2. **Data Visualization**: To gain insights, I created several data visualizations, including pair plots, bar plots, and violin plots. These visualizations allowed me to understand the relationships between variables, particularly with regard to survival status.

3. **Statistical Summary**: I provided a statistical summary of the dataset, including measures such as mean, standard deviation, and quartiles for the continuous variables.

4. **PDF and CDF Analysis**: I generated Probability Density Function (PDF) and Cumulative Density Function (CDF) plots for each of the variables. This analysis helped to understand the distribution of data.

5. **Box Plots and Violin Plots**: Box plots and violin plots were used to visualize the spread of data, especially in relation to survival status. These plots highlighted the variations in data distribution.

6. **Correlation Analysis**: I calculated and visualized the correlation between variables using a heatmap. This analysis helped to identify any linear relationships between the variables.

7. **Strip Plots**: Finally, I used strip plots to visualize the distribution of data points in relation to survival status. These plots provided insights into the data's distribution.

## Insights

- The dataset primarily consists of patients who survived for more than 5 years (1) and a smaller portion of patients who died within 5 years (2).
- Most survivors had 0 to 5 positive nodes, as confirmed by the PDF and CDF analysis.
- The average patient age is 52 years, with the youngest patient being 30 and the oldest patient being 83.
- The dataset spans the years 1958 to 1969.
- The maximum number of positive nodes detected in a patient is 52, but 75% of the patients have 5 nodes or fewer.

These insights and visualizations provide a valuable foundation for further analysis and modeling on this dataset.
