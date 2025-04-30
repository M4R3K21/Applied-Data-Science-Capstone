SpaceX Falcon 9 First Stage Landing Prediction - Capstone Project
Overview
This repository contains the capstone project for the IBM Data Science Professional Certificate and the Applied Data Science with Python Specialization. The project focuses on predicting whether the first stage of the SpaceX Falcon 9 rocket will land successfully. By analyzing launch data, we aim to provide insights for a competing startup to make informed bidding decisions against SpaceX.

Project Motivation
SpaceX has revolutionized space travel by reusing the first stage of its Falcon 9 rocket, significantly reducing costs. A key factor in this is the successful landing of the first stage.

Business Objective:
Predict the likelihood of a successful Falcon 9 first-stage landing to help a competing startup bid more effectively against SpaceX.

Methodology
The project follows the Data Science methodology, including:

1. Data Collection
SpaceX API: Retrieved past launch data in JSON format.

Web Scraping: Extracted additional launch details from Wikipedia.

2. Data Wrangling
Cleaned and processed data.

Calculated launches per site, orbit outcomes, and landing success rates.

3. Exploratory Data Analysis (EDA)
Visualized relationships between flight number, payload mass, launch sites, and orbit types.

Analyzed success rates by orbit and launch site.

4. Interactive Visual Analytics
Folium Maps: Marked launch sites and outcomes (success/failure).

Plotly Dash Dashboard: Created interactive charts (pie charts, scatter plots).

5. Predictive Analysis
Built and evaluated classification models (Logistic Regression, SVM, Decision Trees, KNN).

Best Model: K-Nearest Neighbors (KNN) with 94.4% accuracy.

Key Findings
Success Rate: 98 successful missions, 1 in-flight failure.

Landing Outcomes: Most common successful outcome was "drone ship landing" (5 cases).

Payload Mass: Average payload for F9 v1.1 was 2,928.4 kg; NASA CRS missions totaled 48,213 kg.

Orbits: LEO and GTO orbits had the highest success rates.

Technologies & Tools
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

SpaceX API

Web Scraping (BeautifulSoup, Requests)

Folium (Interactive maps)

Plotly Dash (Dashboard)

SQL (Data querying)



