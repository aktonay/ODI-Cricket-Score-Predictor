## 🏏 Cricket Score & Win Prediction

This project is a **machine learning-based system** that predicts cricket match scores and the probability of winning based on match context, team performance, and live inputs. It integrates several ML models to forecast the **final score**, **team win probability**, and **in-match analytics** through an interactive interface.

---

### 🚀 Features

- Predict **final team score** using:
  - Linear Regression
  - Random Forest Regressor
  - Artificial Neural Network (ANN)
  - ElasticNet Regression
- Predict **match winner** using classification models
- Real-time input through **ipywidgets** interface
- Built-in **data preprocessing**, **encoding**, and **model evaluation**
- Performance metrics: MAE, MSE, RMSE, Accuracy, Precision, Recall, F1-score

---

### 📁 Dataset

The dataset contains match-specific features such as:

- Batting & Bowling Team
- Overs, Runs, Wickets
- Current Run Rate (CRR)
- Target Score
- Venue, Toss Decision
- Match Result

*Preprocessing includes handling categorical features, encoding, and splitting into train-test sets.*

---

### 📊 Models Used

| Task                 | Model                    |
|----------------------|--------------------------|
| Score Prediction     | Linear Regression, Random Forest, ANN, ElasticNet |
| Win Prediction       | Logistic Regression, Random Forest, ANN            |

---

### 💡 Technologies

- Python (NumPy, Pandas, Scikit-learn, Keras)
- Google Colab
- ipywidgets (for UI)
- Matplotlib / Seaborn (for optional visualizations)
