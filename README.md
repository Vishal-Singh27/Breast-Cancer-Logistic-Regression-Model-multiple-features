# Breast Cancer Prediction System 🧬

This is my project where I build a **Logistic Regression** model to predict whether a breast tumor is **malignant** or **benign**.

---

## 📦 Packages Used

- `numpy` for mathematical operations  
- `pandas` for data handling  
- `matplotlib` for visualization

---

## 📊 Dataset

A small mock dataset used for now:

| mean radius | mean area | target |
|-------------|-----------|--------|
| 12          | 13        | 1      |
| 15          | 24        | 1      |
| 46          | 54        | 0      |
| 60          | 70        | 0      |

- `target` is `1` for malignant and `0` for benign.
- Features are **Z-score normalized**.

---

## 🧠 Model

### 🧮 Logistic Regression

A custom logistic regression model is implemented from scratch using:

- **Sigmoid Function**  
- **Squared Error Cost Function**  
- **Gradient Descent Optimization**

### 🧪 Training

- Uses **Gradient Descent** to optimize weights and bias.
- Loss minimized using **Mean Squared Error (MSE)**.

---

## 📈 Results

After training, the predicted labels (`0` or `1`) are plotted against the `mean radius`.  
The model shows how it distinguishes between benign and malignant tumors based on these two features.
