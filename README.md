# Parkinson Disease Intensity Detection Based on Voice Patterns

**Overview:**
This project aims to predict the severity of Parkinson's disease (PD) based on voice patterns and its characteristics, such as jitter and shimmer, using machine learning techniques. Leveraging Python programming language along with libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn, the project explores the dataset, builds regression models, and evaluates their performance to gain insights into the disease progression.

**Key Findings:**

- Voice Pattern Importance: Characteristics such as age emerged as influential factors in predicting PD severity, highlighting the significance of voice patterns in disease manifestation.
- Model Performance: Random Forest Regression exhibited the best performance among the models considered, achieving high accuracy in predicting PD severity based on voice patterns.
- Avoidance of Feature Combination: Decision not to combine all voice pattern variables into one feature was made, preserving the model's accuracy and interpretability.
- Visualization Insights: Various visualizations, including scatter plots, strip plots, and pair plots, provided valuable insights into the relationships between different voice pattern variables and their impact on PD severity.
- Model Interpretability: Decision trees from the Random Forest model were visualized to understand how the model makes predictions based on voice patterns, enhancing interpretability.

**Methodology:**

- Data Exploration: Utilized Pandas for data loading, cleaning, and preprocessing tasks, ensuring data integrity and consistency of voice pattern features.
- Visualization: Leveraged Matplotlib and Seaborn for creating informative visualizations to explore relationships between voice pattern variables and identify patterns in the data.
- Model Building: Built regression models including Linear Regression, Elastic Net, and Random Forest Regression using scikit-learn to predict PD severity based on voice patterns.
- Model Evaluation: Evaluated model performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R2) score to assess predictive accuracy.
- Feature Importance Analysis: Identified important features using Random Forest feature importance, enabling the selection of top voice pattern features for modeling.

**Conclusion:**

This project demonstrates the effectiveness of machine learning techniques in predicting PD severity based on voice patterns and analyzing factors contributing to the disease. By leveraging Python libraries and tools, actionable insights were derived, aiding in better understanding and management of Parkinson's disease using voice analysis.

For detailed implementation and results, refer to the Jupyter Notebooks and Python scripts available in this repository.

**Technologies Used:**

- Jupyter Notebook
- Python
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
- Graphviz (for decision tree visualization)
- Feel free to explore the project repository for detailed code implementations, visualizations, and additional insights. Your feedback and contributions are greatly appreciated!
