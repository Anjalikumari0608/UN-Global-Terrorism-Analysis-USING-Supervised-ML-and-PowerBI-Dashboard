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

# 📂 Model Comparison
| Model               | Accuracy | Strength                 | Weakness                  |
| ------------------- | -------- | ------------------------ | ------------------------- |
| Logistic Regression | Medium   | Simple, fast             | Cannot capture complexity |
| Decision Tree       | Medium   | Interpretable            | Overfitting risk          |
| Random Forest       | High     | Best performance, stable | Slightly complex          |

# 🏆 Best Model Selection
**Selected Model: Random Forest**

Reason:
* Highest accuracy and F1-score
* Handles complex relationships
* Reduces variance and overfitting
* Performs well on real-world noisy data

# 📊 Power BI Dashboard

<img width="310" height="162" alt="WhatsApp Image 2026-04-27 at 12 31 46" src="https://github.com/user-attachments/assets/9e9fc00f-9a97-4916-9d0a-36cfb77d103d" />

# Power BI Dashboard zip Link
https://drive.google.com/file/d/1bjLezDpg3Hc_5gyam4aKD-uTg6UwxGbt/view?usp=sharing

The Power BI dashboard is divided into 8 pages:

# 📍 Page 1 
<img width="1327" height="738" alt="Main Das 1" src="https://github.com/user-attachments/assets/efd0e0f2-c8f4-4574-a03f-536903f30d68" />

# Cards

* Total attacks 
* Total kills
* Total wounded
* Average casualties

# Slicers

* Year
* Country

# Visualizations

* Weapon type
* Severity level
* High risk regions
* Total attack by attack types 
* Success vs Failure
* Total attack by Year

# 📍 Page 2
<img width="1327" height="742" alt="Dash 2" src="https://github.com/user-attachments/assets/f58da34b-e412-4eb8-81f4-cc7f2cafa618" />

# Slicers

* Country 
* Year

# Visualizations

* Attack vs Casualities by region 
* High risk regions based on Casualities
* Attack success rate
* Key Influencers
* Region wise distribution of attacks 
* Top Deadliest Attack types

# 📍 Page 3
<img width="1312" height="732" alt="OBJ4" src="https://github.com/user-attachments/assets/80b3e96b-2f53-4c81-9315-2db386fa2f13" />
# Visualizations

* Attack Severity analysis
* Attack trend by Severity overtime
* Severity wise Attack in top countries

# Major Insights

* High Severity attacks are rare.
* Low Severity incidents show steady increase.
* High and medium Severity trend remain stable.

**Rest of the pages are combined in the PowerBI Dashboard link pasted above.**






