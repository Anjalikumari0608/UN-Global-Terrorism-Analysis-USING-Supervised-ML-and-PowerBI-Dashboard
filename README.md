# UN-Global-Terrorism-Analysis-USING-Supervised-ML-and-PowerBI-Dashboard

# 📌 Project Overview
The Global Terrorism Analysis using Supervised Machine Learning project focuses on analyzing historical terrorism data to uncover patterns and predict the severity of casualties (Low, Medium, High).

By combining data analytics, visualization, and machine learning models, the project aims to support better security planning and risk assessment.

The workflow includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Model building (Logistic Regression, Decision Tree, Random Forest)
* Model comparison and selection
* Dashboard visualization using Power BI

**PowerBI Dashboard Zip link pasted below.**

# Machine Learning Workflow and PowerBI Overview

<img width="1024" height="1536" alt="WhatsApp Image 2026-04-27 at 11 21 21" src="https://github.com/user-attachments/assets/7ab1046b-a938-4ede-9217-1881288a6057" />

# 🎯 Business Objective
The Business objective of this project is:

*To predict the severity of casualties in terrorist attacks using supervised machine learning techniques.*

Supporting Goals:
* Identify high-risk regions
* Analyze weapon types contributing to higher casualties
* Understand attack success patterns
* Provide data-driven insights for decision-makers

# 📊 Dataset Requirements
📌 Key Features:
* Attack Type
* Weapon Type
* Region / Country
* Year of Attack
* Number of Kills
* Number of Wounded
* Success / Failure
* Target Type

🎯 Target Variable:

Severity of Casualties (Created Feature)

* Low → Small number of casualties
* Medium → Moderate casualties
* High → Large casualties

# 🔍 Exploratory Data Analysis (EDA)

 **Key Insights**
* 🌍 Certain regions (e.g., Middle East, South Asia) show consistently high attack frequency
* 💣 Explosives and firearms are the most commonly used and most lethal weapons
* 📈 Terrorist attacks increased significantly after the early 2000s
* 🎯 Successful attacks tend to result in higher casualties
* 🔐 Areas with lower security preparedness show higher severity levels

# 🤖 Machine Learning Approach
The problem is treated as a multi-class classification task.

# 1️⃣ Logistic Regression
* Simple and interpretable
* Works well for linear relationships
* Acts as a baseline model

**Limitation:**

* Struggles with complex, non-linear patterns

# 2️⃣ Decision Tree
* Rule-based model
* Easy to visualize and interpret
* Captures non-linear relationships

**Limitation:**

* Prone to overfitting

# 3️⃣ Random Forest
* Ensemble of multiple decision trees
* Reduces overfitting
* Handles large datasets efficiently

**Strength:**

* High accuracy and robustness

