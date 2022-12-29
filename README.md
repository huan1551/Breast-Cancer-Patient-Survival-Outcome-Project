# Breast Cancer Patient Survival Outcome
## Project idea & Problem Definition
This project topic is not only important to understand the main factors that influence the
high possibility of death from breast cancer, but also to raise people’s awareness about breast
cancer. Increasing breast cancer cases have forced people all over the world to raise awareness
about the significance of identifying breast cancer and the urgency of taking action. This project
is aimed to answer: 1) Which classification model, logistic, KNN, or AdaBoost, is the best model
when it comes to predicting the survival result (i.e. patient has survived or dead from the breast
cancer) of breast cancer patients? 2) What are the most influential variable(s) when predicting
the outcome of breast cancer patients?
## Project Plan & Methods
The three classification methods that we choose are Logistic Regression, KNN, and
AdaBoost. We are going to compare the performance of those three models using the ROC and
AUC. In addition, we also constructed baseline
models- models directly trained from the “try” dataset (i.e. original distributed dataset without
downsampling) to illustrate how downsampling an imbalanced dataset can improve the overall
model performance. Baseline models follow the same training procedures as the downsampled
model, the only difference is the dataset that those models are trained from. For getting the most
influential variable, we are going to use the variable importance plot from Adaboost to
accomplish this task.
### Description of the Dataset
This database of breast cancer patients was acquired from the SEER Program of the
NCI's November 2017 update, which offers details on population-based cancer statistics. The
dataset included female patients who had been diagnosed between 2006 and 2010 with breast
cancer. In the end, 4024 patients were included after the exclusion of patients with uncertain
tumor sizes, studied regional LNs, positive regional LNs, and patients whose survival months
were less than one month. Since the dataset is provided by the National Cancer Institute (NCI)
(the federal government's principal agency for cancer research and training), and the dataset does
3
not have missing values or duplicated data, it has high reliability to be considered valid and
valued data to analyze.
