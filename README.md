🎬 Movie Rating Prediction
 ---

📌 Project Overview
--
This project uses a dataset of the Top 1000 IMDb movies to build a machine learning model that predicts movie ratings. The dataset contains rich movie metadata, including genre, director, cast, popularity, and revenue, making it suitable for both analysis and predictive modeling.

About Dataset:

- 1000 movies with detailed metadata
- IMDb ratings & Metacritic scores
- Genre, runtime, director, and cast
- Popularity (votes) & revenue (gross)
- Short movie overview

📊 This dataset is ideal for:

- Exploratory Data Analysis (EDA)
- Rating prediction models
- Trend and genre analysis
- Data visualization projects
 ---

🎯 Task Description
---

Build a model to predict movie ratings based on available features by:

- Preprocessing the data
- Applying regression-based modeling
- Evaluating model performance

  ---
  
🛠️ Tools & Libraries
---

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

 ---

🔄 Project Workflow
---

1. Data Overview
   - Understanding dataset structure and features

2. Data Cleaning
   - Handling missing values
   - Fixing data types
   - Removing irrelevant columns

3. Exploratory Data Analysis (EDA)
   - Distribution analysis (histograms)
   - Genre vs Rating (boxplot)
   - Popularity vs Rating
   - Meta Score vs Rating
   - Correlation heatmap
   - ANOVA (statistical significance)

 <img width="1489" height="955" alt="image" src="https://github.com/user-attachments/assets/7ccbaced-27de-4a23-b359-baa942184332" />


4. Feature Engineering
   - Genre simplification (Main Genre)
   - Director grouping
   - Log transformation (votes & gross)

5. Preprocessing
   - Feature-target split
   - Encoding categorical variables
   - Scaling numerical features

6. Modeling
   - Linear Regression
   - Random Forest
   - XGBoost

7. Model Comparison
   - Evaluated using MAE, RMSE, and R²

8. Hyperparameter Tuning
  - Optimization using RandomizedSearchCV

🏆 Best Model: Random Forest
   - Achieved highest R² and lowest error

 <img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/7b4bc3f3-cb20-4398-b81f-e56e3df7c0c5" />

---

📊 Key Insights
---

- Popularity (votes) is the strongest driver of movie ratings
- Meta score reflects the importance of critical reviews
- Genre and director also influence audience perception

  ---
  
📈 Feature Importance (Top Drivers)
---

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/f6feed81-8ebb-4950-9a08-6afd235def80" />

 ---
 
🧠 Conclusion
---

Movie ratings are influenced by a combination of popularity, quality, and content characteristics, with audience engagement emerging as the most dominant factor.
 
