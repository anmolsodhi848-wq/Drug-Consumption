# Drug-Consumption

## Project Objective
This project analyzes drug consumption patterns using demographic, behavioral, and personality-trait data to uncover correlations and risk indicators, leveraging Tableau dashboards to explore how factors like age, gender, emotionality, impulsiveness, and social behavior influence the frequency of soft, hard, and recreational drug use, ultimately providing insights into consumption trends, addiction risks, and personality-substance use relationships.


## Dataset Used

https://github.com/anmolsodhi848-wq/Drug-Consumption/blob/main/Drugs.xlsx


## 📊 Key Performance Indicators (KPIs)

1. **Overall Drug Usage Score** – Measures the combined frequency and intensity of consumption across all substances.
2. **Soft Drug Use Index** – Tracks usage levels of substances like cannabis, caffeine, nicotine, and alcohol.
3. **Hard Drug Use Index** – Quantifies consumption of high-risk substances such as heroin, crack, cocaine, LSD, and meth.
4.** Recreational Drug Frequency** – Measures the frequency of leisure-based drug use (e.g., ecstasy, mushrooms, ketamine).
5. **Addiction Risk Score** – Predicts an individual's likelihood of developing dependency based on consumption patterns and behavior traits.
6. **Impulsivity & Self-Control Scores** – Evaluates how behavioral factors influence drug-use tendencies.
7. **Emotionality Score** – Assesses the correlation between emotional stability and substance use.
8. **Personality Influence Index** – Measures how personality traits (Big Five: OCEAN) relate to drug consumption.
9. **Demographic Drug Use Comparison** – Tracks drug usage variations across age groups, gender, and country.
10. **High-Risk User Identification Rate** – Indicates the proportion of individuals falling into high-risk consumption categories.


## Process

1. **Data Preparation (Excel Source):** Imported the raw Excel dataset containing demographic attributes, personality scores, drug labels, and consumption frequencies. Cleaned missing values, standardized column names, and validated data types for accurate analysis.
2. **Data Structuring & Feature Categorization:** Organized variables into logical groups—soft drugs, hard drugs, recreational drugs, demographics, personality traits (OCEAN), and behavioral indicators. Created derived metrics such as Overall Drug Usage, Addiction Risk Score, and Frequency Indexes.
3. **Dashboard Development (Tableau):** Connected the cleaned Excel file to Tableau, designed interactive dashboards, and applied filters for age, gender, drug type, and personality traits. Built visual KPIs, trend analysis, and comparison charts to highlight consumption patterns.
4. **Insights & Validation:** Interpreted dashboard outputs to identify correlations and high-risk behavior patterns. Verified findings through cross-variable comparisons and ensured visual accuracy and usability for decision-making.


## Dashboards

1. **Demographics Distribution**
   <img width="1817" height="723" alt="image" src="https://github.com/user-attachments/assets/f8a7c386-86d8-4931-bff4-d1f4fae0bdf1" />

2. **Personality Traits**
   <img width="1827" height="726" alt="image" src="https://github.com/user-attachments/assets/28b02e1e-8e46-4f1b-8149-f4481da75cfc" />

3. **Drug Consumption**
   <img width="1805" height="740" alt="image" src="https://github.com/user-attachments/assets/d57aae1a-5997-4190-bdba-34c4e74da9fe" />


## 📈 Project Insights

1. **Demographic Patterns**
    1. The dataset is almost gender balanced, with an equal distribution of males and females.
    2. Young adults (18–34) form the largest share of the population and are the primary contributors to drug usage trends.
    3. Most participants come from the United States, making it the dominant geographical segment.
    4. White ethnicity is overwhelmingly represented, influencing overall consumption patterns.

2. **Education & Personality Traits**
   1. The majority of users have completed Some College or a Bachelor’s Degree, indicating higher participation from moderately educated groups.
   2. Personality scores (N-score, Impulsivity, SS Sensation Seeking) show noticeable variance across education levels, with some college groups displaying higher        impulsive and sensation-seeking traits.
   3. A clear upward trend is visible between Sensation Seeking (SS) and Impulsivity, especially among males, linking these traits to higher-risk behaviors.

3. **Drug Consumption Behaviors**
   1. Alcohol and Cannabis are the most widely consumed substances, with a significant portion using them weekly or daily.
   2. Hard drugs like Heroin and Coke show very low active usage, with a majority falling under “Never Used.”
   3. Cannabis consumption displays a diversified pattern, with noticeable usage across daily, weekly, and monthly categories.
   4. Alcohol consumption is significantly high, with over 65% reporting usage in the last week or last month.

5. **Risk Indicators & Behavioral Insights**
   1. Higher impulsivity and sensation-seeking scores correlate with more frequent drug use, especially among young and moderately educated groups.
   2. Soft drug users show stronger links to social activity and personality traits, whereas hard drug usage appears more isolated and less behaviorally driven.
   3. There are clear behavioral clusters suggesting that personality traits contribute meaningfully to predicting consumption intensity.


## 📌 Conclusion
1. The analysis highlights a strong correlation between personality traits, particularly impulsivity and sensation-seeking, and higher drug consumption frequency.
2. Alcohol and cannabis emerge as the most commonly used substances, driven largely by younger demographics (18–34).
3. Hard drug usage remains low, indicating that risky consumption behaviors are concentrated primarily in soft and recreational categories.
4. Demographic factors such as education level, age group, and geography also play a significant role in shaping usage patterns, providing a comprehensive       understanding of substance-use trends.


## 🚀 Future Scope
1. Integrating machine learning models (e.g., clustering, risk prediction) to classify users based on consumption patterns and personality traits.
2. Enhancing the dataset with time-series or longitudinal data to study progression of drug use and behavioral changes over time.
3. Expanding dashboards to include interactive forecasting, scenario analysis, or personalized risk assessment models.
4. Incorporating additional datasets such as socioeconomic indicators, mental health scores, or lifestyle habits to widen analytical depth.


## 💡 Recommendations
1. Prioritize deeper analysis of high-impulsivity and high-SS groups, as they form the core high-risk segment for substance abuse.
2. Develop targeted awareness or prevention strategies focused on young adults and college-level education groups, as they exhibit the highest usage patterns.
3. Use the dashboards to continuously monitor early indicators of addiction, especially for substances with increasing daily or weekly use trends.
4. Encourage integration of this analysis into public health or research frameworks to support data-driven interventions and policy insights.
