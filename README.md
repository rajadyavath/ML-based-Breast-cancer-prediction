🧠 Breast Cancer Detection using Machine Learning
A supervised machine learning project focused on diagnosing breast cancer using the Breast Cancer Wisconsin Diagnostic Dataset. This project explores the use of multiple machine learning classifiers to accurately distinguish between benign and malignant tumors, with an emphasis on model interpretability, real-world healthcare relevance, and clinical applicability.

📌 Overview
Breast cancer remains one of the most prevalent and life-threatening diseases globally. Early diagnosis plays a critical role in improving survival rates. This project applies machine learning algorithms to mammographic diagnostic data, aiming to support medical professionals in making faster, more accurate diagnoses.

Using Support Vector Machines (SVM) and other classifiers, we trained models to detect cancerous patterns from features such as radius, texture, concavity, and symmetry.

🧬 Objectives
Utilize supervised machine learning to detect breast cancer.

Compare different algorithms including SVM, Logistic Regression, Random Forest, etc.

Improve model accuracy through hyperparameter tuning and normalization.

Provide insights into which features are most indicative of malignancy.

🎯 Key Features
🏷️ Classification of tumors into Benign or Malignant.

📊 Model Comparisons (SVM, Logistic Regression, Random Forest).

📈 Achieved 97% accuracy with optimized SVM model.

🧪 Implemented data normalization and parameter tuning for improved performance.

🖼️ Basic GUI/web app (optional) for demo-based predictions (if applicable).

📊 Dataset
Dataset used: Breast Cancer Wisconsin (Diagnostic) Dataset

Available via sklearn.datasets.load_breast_cancer

569 instances with 30 numeric features derived from digitized images of breast masses.

Class distribution: 357 benign, 212 malignant

🧪 Machine Learning Workflow
Data Preprocessing

Checked for nulls, standardized features

Train-Test Split (typically 80–20)

Model Training & Evaluation

Support Vector Machine (SVM): Best performing model (97% accuracy)

Logistic Regression & Random Forest used for benchmarking

Tuned C and gamma parameters via Grid Search CV

Result Optimization

Achieved increased accuracy after applying feature scaling

Evaluated with Confusion Matrix, Accuracy, Precision, Recall

🚀 Installation
To run this project locally:

bash
Copy
Edit
# Clone the repository
git clone https://github.com/your-username/breast-cancer-detection-ml.git

# Navigate into project directory
cd breast-cancer-detection-ml

# Install required packages
pip install -r requirements.txt

# Run the notebook
jupyter notebook or open .ipynb in VSCode/Jupyter Lab
📈 Results
Model	Accuracy
SVM (default)	96%
SVM (tuned)	97%
Logistic Regression	93%
Random Forest	94%

Highest accuracy was achieved with SVM after applying data normalization and parameter tuning.

🧠 Technologies Used
Python

Scikit-learn

Pandas

Matplotlib / Seaborn

Jupyter Notebook

(Optional GUI: Tkinter / Flask / Streamlit)

📌 Project Motivation
This project was inspired by the work of:

Dr. Ahmet Mert (Mechatronics Engineering)

Dr. Erdem Bilgili (Piri Reis University)

Dr. Aydin Akan (Izmir Katip Celebi University, Turkey)

It not only introduced me to real-world applications of machine learning in healthcare but also helped me understand the human impact behind the data. The mortality statistics and global cancer reports served as a strong motivator to use my technical skills for meaningful applications.

🫱‍🫲 Contributing
Contributions are welcome!
If you want to improve this project or try different models or visualizations:

bash
Copy
Edit
# Fork the repo
# Create a new branch
# Make your changes
# Create a pull request

🙏 Acknowledgements
Scikit-learn Documentation

UCI Machine Learning Repository

The GreatStack and Krish Naik YouTube Channels

All researchers and clinicians working to detect and cure cancer
