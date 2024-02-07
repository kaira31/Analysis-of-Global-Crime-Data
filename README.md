# Analysis-of-Global-Crime-Data


## Introduction

In an increasingly interconnected world, understanding global crime rates has become crucial for policymakers, law enforcement agencies, researchers, and citizens alike. The analysis of global crime rates provides valuable insights into the prevalence and distribution of criminal activities, enabling us to identify trends, patterns, and areas of concern. This report delves into the comprehensive examination of global crime scores, encompassing both the computation of results and the creation of visualizations to better comprehend the multifaceted landscape of crime around the world.

## Project Objective

This research aims to comprehensively explore global crime rates, delving into methodologies, data sources, and variables used to measure crime prevalence. It seeks to uncover challenges in accurately gauging criminal activities within nations and identify countries with the highest and lowest crime rates, highlighting global disparities.

## Research Questions

1. **Measuring Crime Rates**: Exploring methodologies, data sources, and variables for quantifying criminal activities.
2. **Crime Rate Disparities**: Identifying countries with the highest and lowest crime rates to highlight global disparities.
3. **Dominant Crime Types**: Unveiling prevalent crime types in selected countries and their underlying drivers.
4. **Characterizing High/Low Crime Countries**: Analyzing socio-economic indicators, governance structures, and law enforcement strategies.
5. **Temporal Trends and Underlying Factors**: Discerning patterns in crime rates over the years and their influencing factors.

## Data Imputation
In the realm of data-driven insights, the process of transforming raw data into valuable information is a pivotal undertaking. This comprehensive guide takes you through the key stages that pave the way for effective analysis. From the initial step of Data Collection to the intricate stages of Data Cleaning, Data Exploration, and Data Processing, we unravel the intricacies of each phase, offering insights, best practices, and techniques that contribute to the transformation of raw data into actionable insights

## Data Cleaning

The dataset underwent thorough cleaning to boost its accuracy and reliability, including the removal of duplicates to ensure data uniqueness and the implementation of strategies to address missing values through imputation or exclusion. Data types were reviewed and corrected, and a consistent naming convention was established. The process involved identifying and managing anomalies and outliers, applying normalization and scaling to numeric fields for uniformity, and engineering new features while removing unnecessary ones for dataset clarity. Additionally, value ranges were verified, inter-column relationships checked for coherence, and categorical variables were encoded. Skewed distributions received appropriate treatment, and data entry errors were corrected, resulting in a refined dataset ready for in-depth analysis, modeling, and visualization efforts.

## Eploratory Data Analysis (EDA)
## 1. Removing unnecessary columns
We've removed unnecessary columns from the dataset to make it more focused and clear. This helps us concentrate on the important information for analysis, making it easier to find patterns and insights. Getting rid of irrelevant columns helps us work more efficiently with the data that matters most.
## 2. Removing columns for which there are insufficient rows across countries
In order to streamline our dataset and maintain its quality, we've set a threshold of 20 columns. This means that we'll only consider countries with data containing at least 20 columns. This approach ensures that we focus on countries with a substantial amount of information, allowing for more robust and insightful analysis.
## 3. Performing outer merge between the datasets nm(nationmaster) and 2014_world_gdp_with_codes
We are performing an outer merge of data from two distinct datasets, namely "nm" and "2014_world_gdp_with_codes." This merge is centered around the country columns, allowing us to combine information from both sources. An essential aspect of this merging process is that it retains all countries, even if they are exclusively present in one of the datasets.
This strategic approach ensures a comprehensive and inclusive representation of countries' data, coupled with their respective 2014 GDP details. By amalgamating these datasets, we construct a comprehensive overview that effectively captures the diverse range of countries and their economic indicators, thereby facilitating a more holistic understanding of the global economic landscape.
## 4.Performing outer merge between the datasets nm(nationmaster) and Publication Reports
We're performing an outer merge on the dataset "Publication Reports," focusing on specific crime fields like Assault, Kidnapping, Theft, and more. Using a unique code sequence, "abcdefghijk" we loop through various data sources and apply data transformation steps. The aim is to create a comprehensive dataset where we unify crime-related information from different sources, while accounting for variations in country names. By merging and organizing the data through these steps, we're able to generate a consolidated dataset with meaningful insights on crime rates across different countries and crime types.
## 5. We preprocessed the final dataset by filling all NA values with 0 before proceeding with normalization
Before applying normalization techniques, we prepared the ultimate dataset by replacing all missing (NA) values with 0. This step ensures that all data points are accounted for, creating a foundation for accurate normalization procedures.
## 6.Applying Min-Max Normalization for Data Standardization
To ensure fair comparisons and accurate analysis, we've normalized the entire dataset using Min-Max normalization. This technique brings all values to a common scale between 0 and 1, eliminating potential biases from differing measurement units. This process enhances the effectiveness of our analyses by allowing us to focus on relative patterns and relationships among variables. With normalized data, we can make more meaningful interpretations and draw unbiased conclusions.

## Data Visualization

Exploring the complex and multifaceted issue of crime through various visualizations, focusing on different types of crimes, their impacts, and the factors influencing crime. You can see these viaulaizations results in the jupyter notebook. You can check the tableau dashboard in my repository.

## Key Takeaways

- The measurement of crime rates is nuanced, requiring diverse methods and considerations.
- Factors such as socio-economic conditions, urbanization, education, law enforcement effectiveness, and cultural norms impact crime rates.
- The relationship between GDP and global crime rates is complex, influenced by multiple factors including economic opportunities, income inequality, and government resources.

This repository serves as a comprehensive exploration of our efforts to analyze and interpret global crime scores, providing a foundation for informed decision-making and collaborative efforts to combat crime on a global scale.

## Conclusion
This study delves into the complexities of global crime rates, underscoring the challenges in quantifying crime and the need for standardized measurement methods. It highlights how crime rates vary across countries, pointing to the importance of understanding local contexts and factors. The research identifies prevalent types of crimes and the socio-economic forces driving them, offering insights for tailored solutions. By examining trends and underlying factors, it establishes links between societal changes and crime rates. Ultimately, this study enhances our understanding of crime and informs strategies for law enforcement and prevention, advocating for collaborative efforts to foster safer communities worldwide.






