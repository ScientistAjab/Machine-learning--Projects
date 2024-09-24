# Machine-learning--Projects
Objective:

Understand and prepare the dataset for analysis.
Train a predictive model to classify (distinguish) diseased patients (metabolic disorder) from healthy individuals.
Evaluate the model's performance.

Methodology:

Utilized unsupervised learning techniques for initial data exploration and clustering of patient profiles.
Performed extensive data cleaning and transformation to ensure the accuracy and usability of clinical data.
Applied Random Forest, Logistic Regression, and Neural Networks to predict key features contributing to Metabolic Syndrome (MS).
Conducted feature importance analysis to identify critical risk factors linked to the syndrome.
Enhanced model performance through hyperparameter tuning and evaluation using cross-validation techniques.
Achieved accurate predictions and identified potential biomarkers that correlate with MS.

Discussion:

Conducted a comprehensive analysis of a biomedical dataset containing patient demographics, clinical features, and genetic mutations to gain insights into Metabolic Syndrome (MetS).
Employed rigorous data preprocessing, feature engineering, and both unsupervised and supervised learning techniques to extract meaningful information and develop predictive models for MetS.
Unsupervised Learning:
Utilized K-means clustering followed by the elbow method, identifying 4 clusters with the best Silhouette score of 0.422, to gain insights into the underlying structure of the data.
Implemented hierarchical clustering to reveal four distinct patient subgroups, aiding further analysis.
Supervised Learning:
Initially attempted a Decision Tree model, achieving a training accuracy of 80% and precision of 78%, with a testing accuracy of 79%. However, interpretability challenges and overfitting were noted.

Transitioned to Random Forest, which initially yielded a testing accuracy of 81.6% and precision of 63.3%, but faced overfitting as training accuracy reached 100%.

Conducted hyperparameter tuning using grid search and feature selection, identifying best features (age, BMI, health_gen, health_phys, history_stroke, walking_diff) and reducing overfitting by 13%.

Further refined the Random Forest model by optimizing data preprocessing steps, achieving a training accuracy of 98.0% and testing accuracy of 94.3%. This model emerged as the most effective predictive tool for MetS identification in our study.

Analyzed genetic mutations' contributions to MetS using Logistic Regression, revealing a training accuracy of 82.2% and testing accuracy of 79.8%. Important genes such as IRX3 and SLC22A1 were highlighted.

Contributions
Uncovered valuable insights into MetS subgroups and risk factors, enhancing understanding of the disease's complexity.
Improved predictive capabilities for MetS risk using readily available patient data, facilitating early detection and personalized interventions.

Limitations:

Dataset skewed towards non-diseased individuals, affecting model performance.
Missing key features (e.g., family history) limited insights into Metabolic Syndrome (MetS).
Data completeness issues (e.g., smoking history) posed challenges.
Complex models like Decision Trees hindered interpretability and risked overfitting.
Future Directions
Focus on balanced data collection and including more features.
Improve data completeness for better model training.
Utilize simpler models with regularization techniques for better interpretability and generalization.

Conclusions:

This innovative study blends computational techniques with medical research to address Metabolic Syndrome (MetS), a significant health issue exacerbated by modern lifestyles.
The aim is to enhance understanding of MetS, enabling early detection and better treatment.
The research showcases the collaboration between computational experts and medical researchers, revealing hidden insights about MetS and identifying important genes like IRX3 and SLC22A1.
The best predictive model achieved a high accuracy of 94.3%, demonstrating real potential for early detection and intervention.
Highlights the transformative potential of computational methods in healthcare, ultimately benefiting global populations as MetS becomes increasingly prevalent due to lifestyle choices.

Team Collaboration:

This project was conducted collaboratively by me and my colleague Hosna Gholizadeh.
