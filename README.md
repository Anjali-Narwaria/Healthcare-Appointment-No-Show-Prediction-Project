# Healthcare-Appointment-No-Show-Prediction-Project

A data science and business intelligence project that predicts patient appointment no-shows and visualizes insights to optimize healthcare scheduling.

🚀 Project Overview

Missed appointments (“no-shows”) are a costly challenge for healthcare organizations, leading to inefficiencies and revenue loss. This project applies predictive analytics to model patient attendance behavior and leverages Power BI for actionable, interactive reporting.

✨ Key Features

Predicts likelihood of patient no-shows using a Decision Tree model

Cleans and engineers raw appointment data for analysis

Explores drivers of no-shows (age, weekday, SMS reminders, etc.)

Publishes interactive Power BI dashboard with dynamic KPIs and visuals

Provides recommendations to optimize patient engagement and scheduling

🛠️ Tools Used

Python (Google Colab):

Data wrangling: pandas, numpy

Model building: scikit-learn

Visualization: matplotlib, seaborn

Power BI:

Dashboarding and interactive data visualization

📂 Workflow

Data Import & Cleaning: Load and clean appointment data, handle missing/invalid entries, reformat dates

Feature Engineering: Create new variables (e.g., waiting time, day of week)

Exploratory Analysis: Visualize and summarize patterns leading to no-shows

Model Development: Train a Decision Tree classifier to predict no-shows

Export Results: Save predictions to CSV for BI use

Dashboarding: Build KPIs and charts in Power BI for intuitive stakeholder insight

Optimization: Derive recommendations based on analytics and trends

📊 Dashboard Highlights

KPIs: Total Appointments, Show Rate, SMS Impact, Age Patterns, etc.

Visuals:

Clustered Column chart: No-shows by Gender and SMS

Line chart: No-show Rate by Weekday

Pie chart: No-show By Gender

Funnel Chart: Appointments by No-show

Stacked Column chart: No-show by Age



📈 Results & Recommendations

The predictive model identifies key risks: weekdays, younger/older age, absence of reminders.

Dashboard enables clinics to monitor and drill down into problematic segments.

Recommendations: Send targeted reminders, focus outreach on high-risk slots/patient groups, monitor schedule patterns.


📝 How to Run

Clone repository

Execute Python notebook in Google colab

Open/Download predictions.csv in Power BI (see powerbi dashboard)

Interact with the visuals or extend the analyses


👤 Author

Anjali Narwaria – https://www.linkedin.com/in/anjali-narwaria-1bb498298/

