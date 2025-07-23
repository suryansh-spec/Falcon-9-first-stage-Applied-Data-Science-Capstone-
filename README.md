# Falcon-9-first-stage-Applied-Data-Science-Capstone-

This capstone project applies the data science lifecycle to analyze and predict the success of Falcon 9 first-stage landings by SpaceX. The goal is to identify factors influencing successful landings and build predictive models based on historical launch data.

We began by collecting data from SpaceX’s public REST API and supplemented it with launch records from public repositories. The data was processed to extract key features like payload mass, orbit type, launch site, and booster version.

Following this, we performed data wrangling to handle missing values, format inconsistencies, and feature engineering. Exploratory Data Analysis (EDA) was conducted using both visual tools (matplotlib/seaborn) and SQL queries, helping us uncover trends, correlations, and anomalies.

The final phase focused on predictive modeling using classification algorithms such as Logistic Regression, Decision Trees, K-Nearest Neighbors, and Support Vector Machines. Models were trained, tuned, and evaluated using performance metrics including accuracy, precision, recall, and F1-score. The best-performing model was selected based on cross-validation results.

This end-to-end pipeline demonstrates the practical application of data science in aerospace, with real-time APIs, robust analysis, and machine learning. It highlights how data-driven insights can enhance mission planning and reliability in space exploration.
