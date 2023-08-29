**#Project Title:**
**Breast Cancer Diagnosis using Machine Learning**
This repository contains code and data for a machine learning project that focuses on classifying breast cancer tumors as either malignant or benign based on a set of features extracted from digitized images of fine needle aspirates (FNAs) of breast masses.

**Dataset**
The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) dataset, commonly referred to as the Wisconsin Breast Cancer dataset. The dataset contains the following information:

Number of Instances: 569
Number of Attributes: 30 numeric, predictive attributes and the class
Attribute Information: Features such as mean radius, mean texture, mean perimeter, mean area, mean smoothness, mean compactness, mean concavity, and more.
Class: Malignant or Benign
For detailed information about the dataset, please refer to the DESCR field in the code.

**Project Structure**
The repository is structured as follows:

breast_cancer_diagnosis.ipynb: A Jupyter Notebook containing the code for loading the dataset, performing exploratory data analysis, preprocessing the data, training machine learning models, and evaluating their performance.
README.md: This README file providing an overview of the project.
breast_cancer.csv: The dataset in CSV format.
LICENSE: The license information for the project.
**How to Use**
1. Clone the repository to your local machine using the following command:
git clone https://github.com/Ali-Airian/breast-cancer-diagnosis.git
2. Navigate to the repository directory:
cd breast-cancer-diagnosis
3. Open and run the breast_cancer_diagnosis.ipynb Jupyter Notebook using Jupyter or any compatible notebook environment. This notebook will guide you through the entire process of loading the dataset, preprocessing, model training, and evaluation.

**Dependencies**
The following Python libraries are used in this project:

pandas
numpy
matplotlib
seaborn
scikit-learn
You can install these dependencies using the following command:
pip install pandas numpy matplotlib seaborn scikit-learn

**License**
This project is licensed under the MIT License. See the LICENSE file for more details.

**References**
For more details about the dataset and the original research papers, please refer to the following references:

W.N. Street, W.H. Wolberg and O.L. Mangasarian. Nuclear feature extraction for breast tumor diagnosis. IS&T/SPIE 1993 International Symposium on Electronic Imaging: Science and Technology, volume 1905, pages 861-870, San Jose, CA, 1993.
O.L. Mangasarian, W.N. Street and W.H. Wolberg. Breast cancer diagnosis and prognosis via linear programming. Operations Research, 43(4), pages 570-577, July-August 1995.
**Credits**
This project is based on the Breast Cancer Wisconsin (Diagnostic) dataset, originally provided by Dr. William H. Wolberg, W. Nick Street, and Olvi L. Mangasarian. The dataset is available through the UCI Machine Learning Repository and can be accessed at https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic).

Please feel free to contribute, provide feedback, or use this project for educational purposes.
