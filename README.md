# Medical Insurance Cost Prediction

This Machine Learning project predicts medical insurance costs based on factors like age, gender, BMI, smoking habits, number of children, and region using a Linear Regression model.

---

## 📌 Project Overview

The goal of this project is to analyze medical insurance data and build a predictive model that estimates insurance charges for individuals.

The project includes:
- Data Analysis & Visualization
- Data Preprocessing
- Feature Encoding
- Model Training using Linear Regression
- Model Evaluation using R² Score
- Predictive System for custom user input

---

## 📂 Dataset Features

The dataset contains the following attributes:

- Age
- Gender
- BMI (Body Mass Index)
- Number of Children
- Smoker Status
- Region
- Insurance Charges (Target Variable)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Data Visualization

The project includes visualization of:
- Age Distribution
- BMI Distribution
- Gender Distribution
- Smoker Distribution
- Region Distribution
- Insurance Charges Distribution

---

## ⚙️ Machine Learning Model

### Model Used
- Linear Regression

### Evaluation Metric
- R² Score

### Results
- Training Accuracy: ~75%
- Testing Accuracy: ~74%

---

## 💡 How Users Can Use This Project

Users can easily use this project by opening the Google Colab notebook or cloning the repository.

### Using Google Colab

1. Open the Colab notebook.
2. Click on **File > Save a Copy in Drive**.
3. Run all the cells.
4. Go to the **Predictive System** section.
5. Change the input values with your own data.

Example:

```python
input_data = (31,1,25.74,0,1,0)
```

Format:

```python
(age, gender, bmi, children, smoker, region)
```

Where:
- Gender → Female = 1, Male = 0
- Smoker → Yes = 0, No = 1
- Region:
  - Southeast = 0
  - Southwest = 1
  - Northeast = 2
  - Northwest = 3

6. Run the prediction cell to get the estimated medical insurance cost.

---

### Using GitHub Repository

Users can also clone the repository using:

```bash
git clone <your-repository-link>
```

Then they can run the notebook or Python script locally and give their own custom input data for prediction.
