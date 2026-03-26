## 📌 Project Overview

This project analyzes the nutritional composition and health risks of common Ghanaian foods using **NumPy, Pandas, Matplotlib, and Seaborn.**

I built this as a bridging project to consolidate my understanding of NumPy after completing the fundamentals, applying the core concepts I had just learned to something real and meaningful. 

The goal is to compute caloric values, classify foods by health impact, and assess risk across three health concerns: diabetes, heart disease, and protein balance.


## 🎯 Problem Context

Most Ghanaians consume a wide variety of traditional foods daily without tracking their nutritional composition.

Before making dietary decisions, it is important to first answer foundational questions:

1. How many calories are in the foods we eat every day?
2. Which foods carry the highest risk for diabetes or heart disease?
3. Are we getting enough protein from our typical diet?
4. What does the data tell us about how we eat?

The goal was not just to practice NumPy, but to produce something with real meaning and real insight.

## 🔍 Research Questions

The analysis is structured around the following questions:

1. What is the caloric content of common Ghanaian foods?
2. Which foods fall into healthy, moderate, or high-calorie categories?
3. Which foods pose the highest diabetes risk based on carbohydrate content?
4. Which foods pose the highest heart disease risk based on fat content?
5. How is protein distributed across typical Ghanaian foods?
6. Which foods carry the highest combined overall health risk?

## 📊 Analytical Methods Used

This is a data analysis project built on the following foundations:

1. Calorie computation using macronutrient conversion factors (Fat × 9, Protein × 4, Carbs × 4)
2. NumPy broadcasting for efficient array-level calculations
3. Z-score normalization for fair cross-nutrient comparison
4. Conditional classification using `np.where` for health and risk labeling
5. Descriptive statistics and distribution analysis
6. Correlation analysis between nutrients and caloric output
7. Data visualization (bar charts, heatmaps, scatter plots, regression plots)

> No machine learning models are used in this analysis.

## 🧠 What This Notebook Does

Inside the notebook, you will find:

1. Clear explanations (Markdown) of why each method is used
2. Step-by-step dataset creation and preparation
3. Calorie calculations using NumPy broadcasting
4. Health classifications backed by interpretation (not just numbers)
5. Multi-dimensional health risk analysis (diabetes, heart, protein)
6. Visualizations that support and explain the findings
7. Code comments explaining each step for learning purposes


## 📈 Key Findings

1. Foods like **Groundnut Soup**, **Palm Nut Soup**, and **Fried Rice** are the most calorie-dense and should be eaten in moderation
2. Most Ghanaian staple foods are **carbohydrate-heavy**, indicating elevated population-level diabetes risk
3. **Fat is the strongest driver of caloric increase**, contributing 9 kcal per gram
4. **Protein-rich foods are underrepresented**, suggesting an imbalance in typical Ghanaian diets
5. Foods high in **both fat and carbs** carry the highest combined health risk


## 📁 Project Files

1. `Food_Nutrition_Health_Risk_Analyzer.ipynb` — Jupyter Notebook containing the full analysis, health classifications, risk assessments, and visualizations.
2. `README.md` — Project documentation.



## 🛠️ Technical Stack

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook



## 🚀 Installation & Usage

```bash
## Clone the Repository
git clone https://github.com/TechDiva001/ghanaian-food-nutrition-analyzer.git
cd ghanaian-food-nutrition-analyzer

## Install Dependencies
pip install numpy pandas matplotlib seaborn

## Run the Notebook
jupyter notebook
```
