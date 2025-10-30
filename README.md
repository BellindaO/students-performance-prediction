Student Performance Prediction


🎯 Project Overview


This project uses Data Science and Machine Learning techniques to predict students’ final grades based on various academic and personal factors such as study time, absences, alcohol consumption, and previous grades.



The main goal is to identify key factors influencing academic performance and help educators, parents, and students make data-driven decisions to improve learning outcomes.

📊 Dataset Information


The dataset used is the Portuguese Student Performance Dataset from the UCI Machine Learning Repository.



It contains student data collected from two Portuguese schools and includes attributes related to:

Student demographics

Academic records

Social and behavioral factors

Family and lifestyle influences



Dataset file used:

student-por.csv

🧩 Methodology
Data Loading & Cleaning – Handle missing values, convert categorical data, and ensure data quality.

Exploratory Data Analysis (EDA) – Visualize patterns and relationships between features.

Feature Engineering – Select relevant variables affecting student performance.

Model Building (Regression) – Train regression models (e.g. Linear Regression, Random Forest) to predict final grades (G3).

Evaluation – Assess performance using metrics such as R² and RMSE.

UI Development – Build a simple Streamlit interface to allow users to input student data and get grade predictions interactively.

🧮 Key Findings
Previous grades (G1, G2) and study time are strong predictors of final performance.

Higher alcohol consumption and frequent absences correlate negatively with performance.

Parental support and family background also influence student success.

💻 Technologies Used
Python

Pandas, NumPy – Data analysis & cleaning

Matplotlib, Seaborn – Visualization

Scikit-learn – Machine Learning models

Streamlit – User Interface

Jupyter / Google Colab – Notebook environment

🚀 How to Run


Option 1: Run Notebook (Google Colab or Jupyter)
Open the notebook file:

student_performance_prediction.ipynb

Run all cells sequentially (Ctrl + F9 or “Runtime → Run all”).

The model will train and display visualizations and performance metrics.



Option 2: Run the Streamlit App


If you want to use the interactive UI:



pip install streamlit pandas numpy scikit-learn joblib
streamlit run app.py

📈 Visualization Sample
Correlation heatmap

Distribution of grades

Scatter plots of key features vs performance



(Plots can be viewed directly in the notebook.)

📦 students-performance-prediction
┣ 📜 student_performance_prediction.ipynb
┣ 📜 app.py
┣ 📜 requirements.txt
┣ 📜 README.md
┗ 📂 data
┗ 📄 student-por.csv



👩🏽‍💻 Author


Bella

Aspiring Data Scientist passionate about using data for positive educational and social impact.

📚 Acknowledgements


Dataset courtesy of:



Paulo Cortez, University of Minho, Department of Information Systems
A. Silva, University of Minho, Department of Information Systems


Published at the UCI Machine Learning Repository.

🌟 Future Improvements
Include additional features like school support and health indicators.

Experiment with advanced models (e.g. Gradient Boosting, XGBoost).

Deploy the Streamlit app online for public access.

🏁 Submission Note


This project was developed for the Python for Data Science Workshop, focusing on:

Regression Analysis

Data Visualization

Model Deployment with Streamlit

Documentation and GitHub Presentation


