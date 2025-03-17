# Matplotlib & Seaborn - Airlines Data Visualization

## Project Overview
This project is split into two parts, demonstrating how data visualization is crucial in understanding and communicating data insights. The goal was to explore and visualize U.S. airline delay data using Python's Matplotlib and Seaborn libraries.

- **Part I: Exploratory Data Visualization**: Focused on systematically exploring the dataset, starting with simple visualizations of single variables and progressing to more complex visualizations that illustrate relationships between multiple variables.
  
- **Part II: Explanatory Data Visualization**: Built on the insights from Part I, transforming the exploratory visualizations into polished, explanatory visuals designed to communicate key findings effectively.

## Dataset Information
The dataset, **"Reporting Carrier On-Time Performance Data"**, covers flights within the United States, including carrier names, arrival and departure delays, and the reasons for delays from 1987 to 2022. It was sourced from the Office of Airline Information, Bureau of Transportation Statistics (BTS), and includes data from U.S. air carriers that account for at least half of one percent of domestic scheduled passenger revenues.

The investigation focused on flight delays, examining airline performance and delay types.

## Project Files
- **Raw Data**:
  - `airline_2m.csv` - The raw dataset containing flight delay information.

- **Cleaned Data**:
  - `airline_df.csv` - Cleaned dataset focusing on general flight information.
  - `delay_df.csv` - Dataset specifically focusing on delay types.
  - `top_states_df.csv` - Dataset covering state-level analysis.
  - `trim_df.csv` - A further refined version of the dataset used for visualizations.

- **Jupyter Notebooks**:
  - `Part_I_exploration_template.ipynb` - Contains the exploratory data visualizations. Can be viewed on GitHub or run locally if the raw data is in the same directory.
  - `Part_II_explanatory_template.ipynb` - Contains the explanatory visualizations, refining the insights from Part I.

- **HTML Versions**:
  - `Part_I_exploration_template.html` - HTML version of the exploratory notebook, viewable in any browser.
  - `Part_II_explanatory_template.html` - HTML version of the explanatory notebook, also viewable in a browser.

Both notebooks and HTML files contain visualizations that explore the relationships between airline carriers and delay times, providing insights for potential travelers and stakeholders.