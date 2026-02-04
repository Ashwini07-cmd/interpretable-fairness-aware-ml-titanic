🚢 Titanic Survival Analysis: An Interpretable & Bias-Aware Machine Learning Study

📌 Project Overview
This project presents a research-oriented analysis of the Titanic passenger dataset with a strong emphasis on interpretability, fairness, and ethical evaluation of machine learning models.
Rather than focusing solely on prediction accuracy, the study investigates how and why models make decisions, and whether these decisions differ across demographic groups.

🎯 Research Motivation
Machine learning models are increasingly deployed in real-world systems where decisions impact human lives. However, many models operate as black boxes, offering limited transparency into their decision-making processes.
This project is motivated by the need to:
- Understand model behavior beyond accuracy
- Identify feature-driven decision patterns
- Detect and analyze demographic bias
The Titanic dataset serves as a controlled historical case study to explore these challenges.

🔍 Research Questions
- How do different machine learning models compare in predicting survival outcomes?
- Which engineered features most strongly influence model predictions?
- Do prediction outcomes vary across demographic groups such as gender and passenger class?
- How can interpretability techniques help identify bias and model limitations?
  
🧪 Methodology
The project is structured as a multi-stage research pipeline:
1️⃣ Problem Formulation
 - Defined motivation, research gap, objectives, and questions
 - Framed the problem from a fairness and interpretability perspective

  2️⃣ Exploratory Data Analysis (EDA)
 - Analyzed survival patterns across demographic features
 - Investigated missing data distribution and potential data bias
 - Visualized relationships between key variables

  3️⃣ Feature Engineering
 - Handled missing values using statistically appropriate strategies
 - Engineered meaningful features to enhance interpretability
 - Encoded categorical variables while preserving semantic meaning

  4️⃣ Model Comparison & Evaluation
Implemented multiple classification models including:
 - Logistic Regression
 - Random Forest
 - Support Vector Machine
 - Compared models using accuracy, precision, recall, and F1-score
 - Selected models based on both performance and interpretability
 - 
 5️⃣ Interpretability Analysis
 - Analyzed model coefficients to identify influential features
 - Examined feature importance and decision patterns
 - Focused on transparency rather than black-box optimization
  
 6️⃣ Bias & Fairness Analysis
 - Evaluated model performance across gender subgroups
 - Compared recall and accuracy for survival prediction
 - Identified evidence of demographic bias in predictions
   
 7️⃣ Limitations & Future Research
 - Discussed dataset constraints and historical bias
 - Highlighted limitations of classical models
 - Proposed extensions using causal inference and advanced explainability methods

📊 Key Findings
- Gender and passenger class strongly influence survival predictions
- Logistic Regression offers superior interpretability compared to complex models
- Prediction recall differs significantly between demographic groups
- Interpretability analysis reveals implicit model bias despite acceptable accuracy
- 
🛠 Technologies Used
- Programming: Python
- Libraries: Pandas, NumPy, Scikit-learn
- Visualization: Matplotlib, Seaborn
- Environment: Jupyter Notebook
- Concepts: Feature Engineering, Model Evaluation, Interpretability, Fairness Analysis
  
📌 Conclusion
 - This project demonstrates that high-performing machine learning models are not necessarily fair or interpretable.
 - By integrating model comparison, interpretability, and bias analysis into a unified framework, the study emphasizes the importance of ethical and transparent AI development.
   
🌱 Future Work
 - Introduce causal inference methods
 - Extend fairness evaluation to additional sensitive attributes
 - Compare with deep learning models under interpretability constraints
