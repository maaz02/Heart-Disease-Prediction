## Synopsis

India faces one of the highest burdens of cardiovascular disease (CVD) globally. Annual CVD-related deaths were projected to rise from **2.26 million (1990)** to **4.77 million (2020)**. With additional risks posed by the COVID-19 pandemic, early and accurate prediction of heart disease has become increasingly important.

This project aims to develop a **Machine Learning model using Logistic Regression** to classify whether a person has heart disease based on health-related parameters.

---

## Objective

- Build a **predictive ML model** to determine the presence of heart disease.
- Use health attributes such as **age, weight, blood pressure, cholesterol, glucose level**, and lifestyle habits to predict outcomes.
- Achieve higher accuracy by expanding on essential parameters and historical patient data.

---

## Current System

- Uses **basic health parameters** (e.g., blood pressure, height, weight).
- Trained on a dataset with **44,948 records**.
- Provides predictions but has certain **limitations**:
    - **No family history data** (a crucial factor in heart disease risk).
    - **No user-friendly interface** (requires technical assistance to run).

---

## Proposed System

The proposed system aims to enhance **prediction accuracy (73.65%)** by using a richer set of **12 attributes**:

| Attribute | Description |
| --- | --- |
| Age | Age in years |
| Gender | Female = 0, Male = 1 |
| Height | Height in cm |
| Weight | Weight in kg |
| BMI | Body Mass Index (calculated from height & weight) |
| Ap_hi | Systolic blood pressure |
| Ap_lo | Diastolic blood pressure |
| Cholesterol | 1 = Normal, 2 = Above Normal, 3 = Well Above Normal |
| Gluc | 1 = Normal, 2 = Above Normal, 3 = Well Above Normal |
| Smoke | Binary: Smoker or Not |
| Alco | Binary: Alcoholic or Not |
| Active | Binary: Physically Active or Not |

These attributes help create a more robust system that improves classification accuracy.

---

## Advantages

- Uses **12 health and lifestyle parameters** for better predictions.
- Achieves **73.65% accuracy** in heart disease prediction.
- Provides a **scalable framework** that can be extended with additional data (e.g., family history, other diseases).

---

## Tools & Technologies

- **Programming Language**: Python
- **Libraries**:
    - NumPy
    - Pandas
    - Scikit-learn
- **Development Environments**:
    - Google Colab
    - PyCharm

---

## Model Details

- **Algorithm**: Logistic Regression
- **Dataset Size**: 44,948 records
- **Accuracy**: 73.65%

---

## Limitations & Future Scope

- Current dataset lacks **family history** and other significant risk factors.
- No **Graphical User Interface (GUI)** for easy usage.
- Future improvements could include:
    - Integrating more parameters (e.g., genetic history, post-COVID data).
    - Deploying the model with a web or mobile interface for accessibility.
    - Using advanced models (e.g., Random Forest, XGBoost, Neural Networks) for higher accuracy.

---

## Conclusion

This project demonstrates how **Machine Learning (Logistic Regression)** can be applied to **predict heart disease risk** with reasonable accuracy. While the system shows promise, integrating additional data and building a user-friendly interface would make it more impactful in real-world healthcare applications.
