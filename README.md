# Vegetable_Classifier
Title Page
Problem Statement: Build a machine learning model to classify vegetables into categories based on their nutritional content (e.g., high protein, high fiber, low calorie, etc.).
Name: Aviral Dixit
Roll Number: 202401100300081
Course: Artificial Intelligence
Date: 22/04/2025

Introduction
This project aims to classify vegetables based on their nutritional profiles into various health categories such as high protein, high fiber, low calorie, etc. This classification can help consumers and dietitians make informed food choices and design personalized diets. We use a dataset consisting of various vegetables with nutritional values such as calories, proteins, carbs, fats, and fiber.

Methodology

Dataset:

1. The dataset contains nutritional information (in grams or kcal per 100g) of a variety of vegetables.

2. Features include: Calories, Protein, Carbohydrates, Fat, Fiber, etc.

3. Labels include: High Protein, Low Calorie, High Fiber, etc.

Preprocessing:

1. Cleaned null values.

2. Normalized feature values to bring them to a common scale.

3. Encoded categorical labels using LabelEncoder.

Model:

1. Used a Random Forest Classifier due to its robustness and interpretability.

2. Performed train-test split with 80-20 ratio.

3. Used accuracy and confusion matrix as evaluation metrics.
