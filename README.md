Project Overview

This project focuses on predicting the recovery time (in days) after disasters using data analytics techniques in IBM SPSS Modeler. The goal is to understand how different factors such as economic loss, disaster severity, and casualties influence recovery duration.
The project applies a no-code visual modeling approach using SPSS Modeler nodes, making it accessible and efficient for data analysis and prediction.

🎯 Objectives
Predict disaster recovery time (recovery_days)
Analyze key factors affecting recovery duration
Build a predictive model using Auto Numeric Node
Evaluate model performance using statistical metrics

📊 Dataset
The dataset used is a Global Disaster Response Dataset (2018–2024) containing information about different disasters.
🔹 Key Features:
disaster_type – Type of disaster
economic_loss_usd – Financial damage
severity_index – Disaster intensity
casualties – Number of affected people
recovery_days – Recovery time (Target Variable)
⚙️ Tools & Technologies
IBM SPSS Modeler
Data Mining Techniques
Predictive Analytics
🔄 Workflow
File → Type → Data Audit → Partition → Auto Numeric → Analysis
🔹 Steps:
Data Import – Load dataset into SPSS Modeler
Data Preparation – Assign variable types and roles
Data Audit – Check data quality
Partitioning – Split data into training and testing sets
Model Building – Use Auto Numeric for prediction
Evaluation – Analyze model performance
📈 Results
Linear Correlation: 0.968 (High accuracy)
Mean Absolute Error: ~4 days
🔍 Interpretation:
Higher economic loss leads to longer recovery time
Disaster severity significantly impacts recovery duration
Model predictions are highly reliable
✅ Conclusion

The project successfully demonstrates how predictive analytics can be used to estimate disaster recovery time. The model achieved high accuracy and can help in planning and decision-making for disaster management.
