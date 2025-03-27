# Health585
conducted EDA and visualization on patient health records using python .Implemented K-Means clustering to group patients based on key health indicators . Developed a KNN-based prediction model to identify patients at risk of certain diseases
Health Analysis: Clustering & Classification
1. Project Overview
This project explores health-related data using Exploratory Data Analysis (EDA) and machine learning techniques. It applies K-Means Clustering and K-Nearest Neighbors (KNN) to classify individuals based on health-related factors.

2. Dataset
Source: (Kaggle.)
Key Columns:
age – Age of the individual
bmi – Body Mass Index
blood_pressure – Blood pressure level
cholesterol – Cholesterol level
exercise_hours_per_week – Average exercise hours per week
health_status – Categorized as Healthy, At Risk, or Unhealthy
3. Tools & Technologies Used
Python: Pandas, NumPy, Matplotlib, Seaborn
Machine Learning Models: K-Means Clustering, K-Nearest Neighbors (KNN)
Jupyter Notebook for analysis
4. Project Workflow
✔ Data Preprocessing – Handling missing values, normalizing data
✔ Exploratory Data Analysis (EDA) – Identifying trends and correlations using visualizations
✔ Clustering (K-Means) – Grouping individuals based on health attributes
✔ Classification (KNN) – Predicting an individual's health status based on input features
✔ Evaluation – Assessing model performance using accuracy and visualization

5. Key Insights
📌 Individuals with high BMI and low exercise levels are more likely to be in the At Risk or Unhealthy category
📌 There is a strong correlation between high cholesterol levels and high blood pressure
📌 The KNN model achieved an accuracy of 85% in predicting health status


7. Future Improvements
🔹 Include additional health factors such as dietary habits and sleep patterns
🔹 Experiment with other classification models like Random Forest 
🔹 Develop a Streamlit dashboard for real-time health data visualization
Health Analysis Dashboard
🚀 An interactive dashboard where users filter health data based on Gender, Blood Pressure, Diabetes, and Medication Adherence. The app finds the corresponding Age and BMI, which are then used as inputs for a Gradio model to predict health risks.

🛠 Features
✅ Two-step process:
1️⃣ Streamlit App: Finds Age & BMI based on user filters
2️⃣ Gradio Model: Predicts Health Risks based on Age & BMI
✅ Sidebar filters for:

Gender
Blood Pressure
Diabetes Status
Medication Adherence
✅ Displays Age & BMI for the filtered data
✅ Gradio Model predicts health risks based on Age & BMI
📌 Installation
Clone the repository:

sh
Copy
Edit
git clone https://github.com/Jimmie585/health-analysis-dashboard.git
cd health-analysis-dashboard
Create a virtual environment ():

sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install dependencies:

sh
Copy
Edit
pip install -r requirements.txt
🚀 Usage
1️⃣ Step 1: Run the Streamlit App
sh
Copy
Edit
streamlit run health_dashboard_v2.py
Use the sidebar to filter by Gender, Blood Pressure, Diabetes, and Medication Adherence.
The app will display the corresponding Age & BMI.
2️⃣ Step 2: Run the Gradio App
sh
Copy
Edit
python gradio_health_risk.py
The Age & BMI found in Step 1 become inputs for the Gradio model.
The model predicts the health risk level based on Age & BMI.
Click the link to open the Gradio web app.
📊 How It Works
🔹 Streamlit App (Step 1)
Select values for Gender, Blood Pressure, Diabetes, and Medication Adherence from the sidebar.
The app filters the dataset based on the selected options.
It displays the corresponding Age & BMI for the filtered records.
🔹 Gradio App (Step 2)
The Age & BMI found in the Streamlit app become inputs for the Gradio model.
The model predicts the health risk level (e.g., Low, Moderate, High).
The output is displayed in the Gradio web UI.
🛠 Technologies Used
Python
Streamlit (for filtering and displaying Age & BMI)
Gradio (for predicting health risks)
Pandas
NumPy

9. Author
👤 James Ndungu
📧 Email: your.jamesndungu.dev@gmail.com
🔗 linkedin.com/in/james-ndungu-803748322
🔗 github.com/kiddo585 

