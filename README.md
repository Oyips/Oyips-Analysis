# Oyips-Analysis
Oyip's Analysis

«We let the data talk.»

Oyip's Analysis is a collection of practical data analysis and data science projects focused on understanding real-world questions through data, statistics, mathematics, machine learning, and scientific reasoning.

The goal is not simply to build models, but to understand the patterns in the data, what they mean, and where their limitations lie.

---

What You'll Find Here

- Exploratory Data Analysis
- Statistical analysis
- Data visualization
- Mathematical modelling
- Machine learning
- Real-world datasets and questions
- Scientific and quantitative reasoning

---

Projects

Week 01 — Vehicle Weight & Fuel Efficiency

Question:

«Does vehicle weight affect fuel efficiency?»

Using the Auto MPG dataset, this analysis investigates the relationship between vehicle weight and fuel efficiency and explores how other vehicle characteristics influence that relationship.

Key Findings

- Weight and fuel efficiency showed a strong negative correlation: r = -0.832
- A simple linear model using weight explained approximately 69.2% of the variation in MPG.
- Weight and horsepower were strongly related: r = 0.865
- Adding horsepower increased the model's explanatory power to approximately 70.6%.
- Adding model year increased the training R² to approximately 80.8%.
- On a held-out test set, the final model achieved:
  - R² = 79.2%
  - MAE = 2.51 MPG

Main Insight

The data shows a strong association between vehicle weight and fuel efficiency, but weight does not tell the entire story.

Other factors such as horsepower and model year also contain substantial information about fuel efficiency. This highlights an important principle in data analysis:

«A strong relationship between two variables does not necessarily mean one variable alone explains the outcome.»

The analysis also connects the statistical findings with physical intuition: heavier vehicles generally require more energy to accelerate and move, while engine characteristics, vehicle design, and technological changes also influence fuel consumption.

"View the Week 1 notebook" (./oyips-analysis-week-01.ipynb)

---

Analytical Approach

Each analysis follows a simple process:

Ask → Explore → Measure → Model → Evaluate → Interpret

The aim is to allow evidence to guide the conclusion rather than forcing a conclusion onto the data.

---

Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Git & GitHub

---

Philosophy

«A model should help us understand reality, not just predict it.»

Good analysis goes beyond obtaining a number.

It asks:

- What does the number mean?
- Why might the pattern exist?
- What else could explain it?
- What can the data actually support?

---

More Projects

This repository will grow with new investigations covering areas such as:

- Statistics
- Data Science
- Machine Learning
- Mathematics
- Physics
- Real-world quantitative problems

---

Oyip's Analysis — We let the data talk.
Approach

Each analysis follows a simple principle:

Ask → Explore → Measure → Model → Interpret

The objective is to let the evidence guide the conclusion rather than forcing a conclusion onto the data.

Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Git & GitHub

Philosophy

«A model should help us understand reality, not just predict it.»

Oyip's Analysis — We let the data talk.
