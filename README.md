**Task 1 at Prodigy: House Price Prediction**

I explored and compared two regression models to understand how different approaches impact performance:
1️⃣ Simple Linear Regression
2️⃣ Advanced Regression Pipeline (Polynomial Features + Ridge Regularization)

What I Did and Why:
Data Preprocessing:
✔ Cleaned the data by removing duplicates and handling missing values.
✔ Standardized features (like square footage, bedrooms, bathrooms) for uniformity and fair comparisons.

Simple Linear Regression:
🔹 A straightforward model to establish a baseline.
🔹 Performed exceptionally well, achieving an R² score of 0.3597959820405514.

Advanced Regression Pipeline:
🔹 Integrated Polynomial Features to capture non-linear patterns.
🔹 Added Ridge Regularization to control overfitting on complex relationships.
🔹 Achieved an R² score of 0.16643119950893936, which was lower than Simple Linear Regression, likely due to over-smoothing for this dataset.

Visualization & Evaluation:
📈 Evaluated metrics like R² and MSE to assess performance.
