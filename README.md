# Disease-Symptom-Analysis

Project Description

This project focuses on analyzing the relationship between various symptoms and possible diseases using the Disease-symptom.csv file. The original dataset contains 4,920 records, but we used a random sample of 1,000 records for this analysis.

Understanding these relationships is valuable for assisting healthcare professionals and researchers in diagnosing diseases based on presented symptoms.

⸻

Data Preprocessing

The preprocessing steps included:
	•	Loading the data into a Pandas DataFrame
	•	Handling missing values
	•	Removing duplicates
	•	Normalizing numerical data
	•	Tokenizing symptom text fields
	•	Validating symptom-disease relationships

These steps ensured a clean, accurate, and reliable dataset ready for analysis and visualization.

⸻

Analysis

For statistical analysis, we used the statistics library to compute:
	•	Mean
	•	Median
	•	Mode

We also used Pandas to:
	•	Calculate the correlation matrix
	•	Perform word frequency analysis using Series.value_counts()
	•	Group and aggregate data using groupby()

⸻

Visualizations

To explore and present the data visually, we used:
	•	Matplotlib
	•	Seaborn

We applied various types of visualizations to show the relationships between symptoms and diseases. The selection of each chart type was based on data suitability, allowing for the most effective and meaningful representation of insights.
