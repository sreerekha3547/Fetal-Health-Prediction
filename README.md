# Fetal-Health-Prediction
Applied Machine Learning

DSCI 631 Project Proposal: Fetal Health Prediction

Introduction:

Child mortality reduction is an important indication of human development and is reflected in several of the United Nations' Sustainable Development Goals. By 2030, the United Nations wants nations to have eliminated avoidable deaths of newborns and children under the age of five, with all countries aiming to decrease under-five mortality to at least 25 per 1,000 live births. Maternal mortality, which accounts for 295 000 fatalities during and after pregnancy and delivery, runs parallel to the concept of child mortality (as of 2017). The great majority of these deaths (94%) happened in low-resource areas, and the majority of them could have been avoided.

Cardiotocograms (CTGs) are a straightforward and inexpensive way for healthcare practitioners to monitor fetal health and take measures to reduce child and mother death. The machine sends ultrasound pulses and reads the response, providing information on the fetal heart rate (FHR), fetal movements, so on.

Team Members:

Grace Sigalla (gas83@drexel.edu) is currently pursuing a master's degree in Data Science, this being her second quarter here at Drexel University. Grace has a background in business administration from her undergraduate and worked for two years as an Admissions Manager for a nonprofit organization. Grace is adaptable, goal oriented and works well in a team. Grace has experience working with tools such as Microsoft Excel and Access, for doing data analysis and aggregation. She looks forward to using her newly learnt Python skills in doing data analysis for this project, and in the process continues learning more from fellow team members.

Gowtham Vaddanam (gv336@drexel.edu) is pursuing his master’s degree in Data Science as a Full-time Student. He completed his undergraduate in Computer Science & Engineering. He had been an intern as a Python Developer for a couple of months during his B.Tech. His inquisitive nature drove him to learn the underlying concepts of programming frameworks in R and Python. He wants to bridge his skillset in analysis methods with interpretation via statistical, algorithmic and mathematical reasoning from this class and from peer members. And he is looking forward to contributing to the group efforts by assisting with the technical aspects of data processing and Interpretation to the best of his current abilities.

Sreerekha Rajendran (sr3547@drexel.edu) is working towards a master's degree in Data Science. Sreerekha is a skilled presenter and team player who has experience working with Python and SQL, as well as various data visualization techniques. She completed her undergraduate degree in Computer Science. As part of the project team, she will look forward to expand her skillset as a Python programmer and gain additional experience in data analysis and interpreting interesting insights from it to draw useful results. She also looks forward to improving her technical Python skills in ways that will benefit her future projects, work-related and otherwise.

Goal:

Our main aim in this project is to use machine learning to classify and predict fetal health which in turn can prevent fetal and maternal mortality. We intend to use classification algorithms to achieve the lowest error in prediction.

Data:

The dataset chosen for this project has features extracted from Cardiotocogram exams, and classified by expert obstetricians.

Source: Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318

Link to Dataset: https://www.kaggle.com/code/karnikakapoor/fetal-health-classification/data|

Algorithms intended to apply:

According to the description of the datasets, pre-processing was already completed. Therefore, our next steps are to just prepare and pass the data into the models that we want to predict. 
We are planning to build classification task for predicting the child mortality and maternity mortality: Logistic regression, Random Forest, and K-nearest neighbors (KNN)

1. Logistic Regression: LR is the standard state-of-the-art architecture for interpreting the labeled outputs of mortality.

2. K-nearest neighbours(KNN): Since the class splits have been separable based on distance for many attributes.

Main advantages of KNN and Logistic regression are robust use in similarity function for estimating the predictor value irrespective of dataset size and simplicity.

3. Random Forest Classifier: While pre-processing the data, the main observation in the data is the limitation of classes - where the pre-dominant group will be given features stack of values. And well-known for ease in generalization.
Most of the attributes labelled as certain class specifically. Hence, Stratified KFold in RandomForest Classifier might be an improvised model.
