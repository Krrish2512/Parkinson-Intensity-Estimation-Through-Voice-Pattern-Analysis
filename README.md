# Parkinson Disease Intensity Detection Based on Voice Pattern Analysis

## Overview
This project focuses on analyzing Parkinson's disease data to identify patterns and insights related to the progression and symptoms of the disease. Utilizing various Python libraries such as NumPy, pandas, Matplotlib, seaborn, and scikit-learn, we perform data preprocessing, visualization, and machine learning tasks to understand the underlying patterns in the data.

## Dataset
The dataset, named `better_data.csv`, contains multiple features related to Parkinson's disease symptoms, including various measures of voice recordings from individuals diagnosed with Parkinson's disease. Key features include jitter, shimmer, total UPDRS (Unified Parkinson's Disease Rating Scale), motor UPDRS, and others.

## Key Features
- **Jitter:** Measures the frequency variation in consecutive periods of a sound waveform.
- **Shimmer:** Measures the amplitude variation in consecutive periods of a sound waveform.
- **Total UPDRS:** A widely used scale that assesses the severity of Parkinson's disease.
- **Motor UPDRS:** Focuses on evaluating motor symptoms associated with Parkinson's disease.

## Usage
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed.
3. Open the `parkinson.ipynb` Jupyter notebook.
4. Run the cells in sequence to load the data, perform exploratory data analysis, preprocess the data, and apply machine learning models.

## Key Findings
1. Jitter and Shimmer Analysis: The analysis of Jitter and Shimmer values, which are measures of frequency and amplitude variations in speech, respectively, showed significant differences between healthy individuals and those with Parkinson's Disease (PD). Higher values of these parameters were observed in PD patients, indicating a potential biomarker for early diagnosis.

2. UPDRS Score Correlation: The Unified Parkinson's Disease Rating Scale (UPDRS) scores, particularly the motor UPDRS scores, showed a strong correlation with both Jitter and Shimmer values. This suggests that as the severity of PD increases, so do the irregularities in speech patterns.

3. Age and Gender Distribution: The dataset analysis revealed no significant correlation between age or gender and the severity of Parkinson's symptoms based on speech metrics. This indicates that the speech impairments in PD are more closely related to the disease's progression rather than demographic factors.

4. Machine Learning Model Performance: The application of machine learning models for predicting PD severity based on speech metrics yielded promising results. Models such as Random Forest and Support Vector Machines demonstrated high accuracy, suggesting that speech analysis can be a viable non-invasive diagnostic tool.

## Conclusion
The study underscores the potential of speech analysis as a non-invasive, cost-effective method for the early detection and monitoring of Parkinson's Disease. The use of technologies such as Python, along with libraries like Pandas, NumPy, and Scikit-learn, facilitated the efficient analysis of speech data. The integration of Praat-Parselmouth further enriched the analysis by providing detailed phonetic insights. The findings highlight the importance of Jitter and Shimmer as biomarkers for PD and suggest that machine learning models can effectively classify and predict the severity of the disease. Future research could focus on refining these models and exploring other speech parameters to enhance diagnostic accuracy.

## Contribution
Contributions to this project are welcome. You can contribute by improving the machine learning models, adding new data visualization techniques, or extending the dataset with more features.
