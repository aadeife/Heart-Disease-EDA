# Heart Disease Exploratory Data Analysis 🫀
Exploratory Data Analysis (EDA) on the Heart Disease UCI Dataset.

## Project Overview
**Objective:** Understand factors and trends associated with heart disease
- Tools: Python, Pandas, Numpy, Matplotlib, Seaborn
- Dataset: [Heart Disease UCI] (https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data?resource=download)

## Summary of Key Findings:
Demographics:
- The dataset is predominantly male (79%) and most participants are between 40-60 years old (67%).

Variables:
- The presence of advanced stages (2, 3, and 4) of heart disease increases with age, with the 60+ group showing the highest instances of advanced stages of disease (49%).

- Visually, higher max heart rates tend to be associated with no heart disease, with an average max heart rate of 128 beats per minute (bpm) in participants with heart disease, and 149 bpm in healthy individuals.

- In those who reported chest pain, asymptomatic chest pain had the highest percentage of heart disease cases (79%). This suggests that silent symptoms of chest pain are critical, while typical/atypical angina and non-anginal chest pain types tend to be associated with healthier cases.

- A higher number of major vessels, as seen through fluoroscopy, present a moderate correlation with the presence of heart disease (r = 0.52).
- Greater ST depression, which reflects reduced blood flow to the heart during exercise, also present a moderate correlation with higher rates of heart disease (r = 0.44).

- Cholesterol levels have a weak association with heart disease in this dataset, suggesting a slightly inverse relationship (r = -0.23). This is surprising as high cholesterol is typically considered a risk factor for heart disease.

Conclusion:
- Overall, the dataset shows that physiological stress indicators (e.g., ST depression), vessel calcification (ca), and lower max heart rate are stronger indicators of heart disease presence.
- The imbalance toward male and healthy participants may influence some findings and should be considered in future modelling.

## Visuals
Plots and figures are saved in the `figures/` folder.

## Reflection
This project helped me practice EDA techniques, data visualization, and understanding clinical data interpretation.


## Citations:
Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
V.A. Medical Center, Long Beach and Cleveland Clinic Foundation:Robert Detrano, M.D., Ph.D.
