# HEALTHCARE_APPOINTMENT_NOSHOW_PREDICTION
HEALTHCARE_APPOINTMENT_PREDICTION
🏥 Healthcare Appointment No-Show Prediction

📌 Project Overview

This project aims to predict whether patients will miss their medical appointments and provide insights to optimize hospital scheduling. By analyzing historical appointment data, we identify key factors influencing no-shows and build a machine learning model for prediction.

---

🎯 Objectives

- Predict patient no-shows using machine learning
- Analyze factors affecting missed appointments
- Build an interactive dashboard for insights
- Provide optimization recommendations

---

🛠 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Power BI (Dashboard Visualization)

---

📊 Dataset

The dataset contains patient appointment details such as:

- Age, Gender
- Appointment & Scheduled Dates
- SMS Reminder status
- Medical conditions (Diabetes, Hypertension, etc.)
- No-show status (Target Variable)

---

🔍 Data Processing

- Cleaned and transformed raw data
- Converted date columns to datetime format
- Created new features like:
  - Waiting Days
  - Appointment Weekday

---

📈 Exploratory Data Analysis

Key insights:

- Patients without SMS reminders are more likely to miss appointments
- Longer waiting times increase no-show probability
- Certain weekdays show higher absentee rates
- Age influences attendance patterns

---

🤖 Model Building

- Algorithm used: Decision Tree Classifier
- Features used: Age, SMS Received, Waiting Days
- Data split into training and testing sets
- Model evaluated using accuracy and classification metrics

---

📊 Power BI Dashboard

Dashboard includes:

- No-show distribution
- SMS vs No-show analysis
- Weekday trends
- Interactive filters (Gender, Neighbourhood, SMS)

---

💡 Optimization Recommendations

- Send automated SMS reminders
- Reduce waiting time for appointments
- Use overbooking for high-risk patients
- Focus on high no-show demographics
- Optimize scheduling based on trends

---

✅ Conclusion

This project demonstrates how data analytics and machine learning can improve healthcare efficiency by reducing missed appointments and optimizing scheduling systems.

---

📁 Project Deliverables

- Python Notebook (Data Cleaning + Model)
- Cleaned Dataset
- Power BI Dashboard (.pbix)
- Project Report
