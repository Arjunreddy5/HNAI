Lung Cancer Detection using Machine Learning
This project aims to analyze and predict lung cancer using a dataset of patient lifestyle and health indicators. The dataset includes attributes like smoking habits, age, gender, alcohol consumption, and symptoms such as chest pain and shortness of breath. Several machine learning models are trained and evaluated to find the most accurate predictor.

📁 Dataset
The dataset is sourced from a public file and contains the following attributes:

GENDER: Male (M) or Female (F)

AGE: Age of the patient

SMOKING, YELLOW_FINGERS, ANXIETY, etc.: Encoded as YES=2, NO=1

LUNG_CANCER: Target variable (YES or NO)

📊 Exploratory Data Analysis (EDA)
Visual analysis includes:

Gender distribution in lung cancer cases

Age distribution of cancer patients

Smoking and alcohol correlation with lung cancer

Heatmap showing feature correlations

⚙️ Data Preprocessing
Converted categorical variables (e.g., GENDER, LUNG_CANCER) to numerical

Scaled the AGE column using StandardScaler

🤖 Machine Learning Models
Trained six models:

Logistic Regression

Support Vector Classifier (SVC)

Decision Tree Classifier

Random Forest

K-Nearest Neighbors (KNN)

Naive Bayes

Model Evaluation
Accuracy scores were computed for each model, and the results were visualized in a bar chart. Accuracy ranged between 90–97%.

📈 Results
The models performed with high accuracy. The best-performing models were selected based on accuracy on the test set.

📂 Output Visuals
Saved figures include:

Gender vs Cancer Distribution (Pie chart)

Cancer Count by Age (Histogram)

Smoking and Alcohol Influence (Pie charts)

Correlation Heatmap

Model Accuracy Comparison (Bar chart)

🛠 Requirements
Python 3.11

Libraries: pandas, numpy, matplotlib, seaborn, sklearn

▶️ How to Run
Clone the repository or run the notebook in Google Colab.

Make sure the necessary libraries are installed.

Execute all cells in the notebook to preprocess data, visualize insights, and train models.
