# Medical Insurance Cost Prediction

## 📌 Project Overview
This project aims to predict medical insurance costs for individuals based on various features like age, BMI, smoking status, and more using **Linear Regression**.

## 📂 Dataset
The dataset used is `insurance.csv`, containing the following columns:

| Feature       | Description |
|--------------|-------------|
| `age`        | Age of the individual |
| `sex`        | Gender (male/female) |
| `bmi`        | Body Mass Index (BMI) |
| `children`   | Number of children/dependents |
| `smoker`     | Smoking status (yes/no) |
| `region`     | Residential region (northeast, northwest, southeast, southwest) |
| `charges`    | Medical insurance cost (target variable) |

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries Used:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

## 🚀 Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Medical-Insurance-Cost-Prediction.git
   cd Medical-Insurance-Cost-Prediction
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook Source Code.ipynb
   ```

## 🔍 Project Workflow
1. **Load Dataset**: Import and explore data.
2. **Preprocessing**:
   - Handle categorical variables using one-hot encoding.
   - Split data into training and testing sets.
3. **Model Training**:
   - Apply **Linear Regression** using `sklearn`.
   - Train the model on `X_train` and `y_train`.
4. **Predictions & Evaluation**:
   - Predict insurance costs on test data.
   - Evaluate model performance using metrics like MAE, MSE, RMSE, and R² score.

## 📊 Results & Evaluation
- **R² Score:** 0.7515

## 📌 Future Improvements
🔹 Try other models like **Decision Trees** or **Random Forest** for better accuracy.  
🔹 Implement **feature scaling** for better model performance.  
🔹 Use **polynomial regression** for more complex patterns.  



---

⭐ If you found this useful, give it a star on GitHub! 🚀



