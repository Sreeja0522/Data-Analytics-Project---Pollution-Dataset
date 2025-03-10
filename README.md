# **Data-Driven Strategies for Enhancing Regional Air Quality Project**

In this project, I have applied a range of machine learning techniques to build a predictive model, including data preprocessing, exploratory data analysis (EDA) and model selection. The machine learning models implemented include classification algorithms like Tree Based Models and Gradient Boosting, as well as regression models such as Logistic Regression.

For the data visualization aspect, I utilized R to generate insightful charts and graphs that highlight trends and relationships between key features. The remaining work, including data cleaning, model building, evaluation, and the generation of actionable recommendations, was done using Python, leveraging libraries such as pandas, NumPy, scikit-learn, and matplotlib.

Through this project, I not only deepened my knowledge of machine learning but also honed my skills in data visualization and model interpretation, providing a solid foundation for future data-driven decision-making in environmental analysis.

**Tools Used:** R and Python.

---
**Table of Contents:**

1)Introduction

2)Scenario

3)Dataset
   
4)PACE stages

5)Result

---
# Introduction

This is my capstone project showcasing my ability to analyze environmental data and provide actionable insights to improve air quality across regions. The primary goal of this project is to predict air quality levels based on various environmental and demographic factors such as temperature, humidity, pollutant concentrations, and proximity to industrial areas.

---
# Scenario

The Environmental Protection Agency (EPA) is facing increasing challenges in managing air pollution across different regions of the country. The agency has been receiving complaints from citizens about poor air quality in certain urban and industrial areas, which is believed to be contributing to various health issues, including respiratory diseases. As part of its ongoing efforts to combat pollution, the EPA is working with local authorities to develop targeted interventions.

To make informed decisions, the EPA requires a data-driven approach that can predict air quality levels and identify key factors influencing pollution. By understanding the relationship between various environmental and demographic factors (such as temperature, humidity, industrial proximity, and population density), the agency can prioritize areas most in need of regulatory actions and community interventions.

Your task is to analyze a dataset that contains information on these factors across several regions, predict the air quality levels, and provide actionable recommendations. The goal is to help the EPA take proactive steps to mitigate pollution in the most affected areas and improve public health.
This dataset focuses on air quality assessment across various regions.

---
# Dataset 

The dataset contains 5000 samples and captures critical environmental and demographic factors that influence pollution levels. You can access the dataset [here](https://github.com/Sreeja0522/Data-Analytics-Project---Pollution-Dataset/blob/main/pollution_dataset.csv).


**Key Features:**

**Temperature (°C)**: Average temperature of the region.

 **Humidity (%)**:  Relative humidity recorded in the region.

 **PM2.5 Concentration (µg/m³)**:  Fine particulate matter levels.

 **PM10 Concentration (µg/m³)**:  Coarse particulate matter levels.

 **NO2 Concentration (ppb)**:  Nitrogen dioxide levels.

 **SO2 Concentration (ppb)**:  Sulfur dioxide levels.

 **CO Concentration (ppm)**:  Carbon monoxide levels.

 **Proximity to Industrial Areas (km)**:  Distance to the nearest industrial zone.

 **Population Density (people/km²)**:  Number of people per square kilometer in the region.


Target Variable: Air Quality Levels:

    Good: Clean air with low pollution levels.

    Moderate: Acceptable air quality but with some pollutants present.

    Poor: Noticeable pollution that may cause health issues for sensitive groups.

    Hazardous: Highly polluted air posing serious health risks to the population.

---

# PACE stages

I followed the PACE stages for the completion of the project, they are:

**Planning:** Define the project goals, problem statement, and scope. Identify datasets, tools, and technologies required. Detailed process in the Google Colab [here](https://github.com/Sreeja0522/Data-Analytics-Project---Pollution-Dataset/blob/main/Plan%26Analyze1.ipynb).

**Analysis:** Explore and preprocess the data. Perform feature engineering, handle missing values, and visualize key patterns. Detailed process in the Google Colab using R  [here](https://github.com/Sreeja0522/Data-Analytics-Project---Pollution-Dataset/blob/main/EDA_using_R.ipynb).

**Construction**: Select and implement suitable machine learning models. Train and validate the models using split datasets (e.g., train/test/validation) [here](https://github.com/Sreeja0522/Data-Analytics-Project---Pollution-Dataset/blob/main/Execution%26Accuracy.ipynb).

**Execution:** Deploy the model in a production environment. Monitor performance, collect feedback, and make iterative improvements.

---
**1. Prediction Accuracy & Model Performance**

XGBoost and Random Forest performed the best, achieving high accuracy (~96%) in predicting air quality levels.
Logistic Regression and SVM struggled, likely due to the complex and non-linear relationships in air pollution data.

**2. Key Factors Affecting Air Quality**

Industrial Proximity: Areas closer to industries exhibited poorer air quality due to emissions from manufacturing and energy production.
Population Density: Highly populated regions experienced worse air quality, likely due to vehicular emissions and urban congestion.
Meteorological Conditions:
Higher temperatures correlated with increased pollutant concentration, possibly due to atmospheric reactions.
Humidity levels played a role in air quality fluctuations, affecting pollutant dispersion and chemical interactions.

**3. Areas of Concern & Recommendations** 

High-Risk Urban & Industrial Zones: Regions with dense population and industrial activity need stricter regulations and emission control measures.
Policy Recommendations:
Strengthen industrial emission standards and enforce compliance.
Promote public transport and emission-reducing measures (e.g., electric vehicles).
Implement real-time air quality monitoring and alert systems.
Community Interventions:
Educate citizens on reducing personal emissions (e.g., carpooling, reducing waste).
Increase green spaces to absorb pollutants and improve air quality.

**4. Future Improvements**

Refine predictive models by incorporating additional environmental and economic factors.
Use real-time sensor data for dynamic monitoring.
Collaborate with local governments to implement data-driven pollution control strategies.
