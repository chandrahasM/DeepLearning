# Fairness in Machine Learning

# Fairness Assessment in Machine Learning
This repository contains code and analysis for evaluating fairness in a machine learning model for psychiatric diagnosis. The focus is on assessing potential biases in the model's predictions across different demographic groups, particularly considering the intersectionality of race and gender.

# Fairness Assessment
Ensuring fairness in machine learning systems is crucial, as biases in the training data or model can lead to discriminatory outcomes for certain groups. In this analysis, we examine a hypothetical scenario where a machine learning model is trained to predict a patient's diagnosis of either affective disorder or schizophrenia based on various features, including race and gender.

# Quantifying Fairness
To quantify fairness, we calculate and compare performance metrics across different demographic groups. Specifically, we focus on the False Positive Rate (FPR) and True Positive Rate (TPR) metrics.

# Fairness Metrics
The fairness metrics used in this analysis are:

False Positive Rate (FPR): The rate at which individuals are incorrectly classified as positive (e.g., diagnosed with schizophrenia when they have an affective disorder).
True Positive Rate (TPR): The rate at which individuals are correctly classified as positive (e.g., diagnosed with schizophrenia when they actually have schizophrenia).
These metrics are calculated for different demographic groups and compared to a reference group (in this case, White Men) to identify potential biases.

# Racial Bias
The initial analysis focuses on assessing racial bias by comparing the FPR across different racial groups. The results show a significant disparity, with Black individuals having a much higher FPR compared to the White reference group, indicating a higher rate of misdiagnosis for Black patients.

# Intersectional Bias
To further explore potential biases, an intersectional approach is taken, considering the intersection of race and gender. The analysis reveals that Black men, in particular, are disproportionately affected by misdiagnosis, with an even higher FPR compared to Black individuals as a whole.

# Feature Evaluation
To better understand the factors contributing to the observed biases, an evaluation of the model's features is conducted. This analysis explores how certain features, such as rumination and tension, vary across different intersectional groups within the affective disorder population, potentially leading to misdiagnosis.

# Conclusions
The analysis highlights the importance of adopting an intersectional approach in fairness assessments, as biases can be masked or exacerbated when considering only single attributes like race or gender. The results demonstrate significant biases in the model's predictions, with Black men being particularly affected by misdiagnosis, as evidenced by their high FPR and relatively low TPR compared to the White Men reference group.

These findings underscore the need for further research and interventions to address the systemic factors contributing to these biases and ensure fair and equitable healthcare outcomes for all individuals, regardless of their race, gender, or other social identities.
