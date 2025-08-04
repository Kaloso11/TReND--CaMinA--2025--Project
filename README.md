# Predicting Mouse Pupil Size from Neuronal Response

This project was developed as part of the TReND-CaMinA 2025 summer school, with the goal of using neural recordings to predict pupil size in mice using machine learning techniques.

## 👥 Contributors

- Kaloso Tlotleng
- Champion Lumamba
- Ronald Omolo Ouma
- Farhanah Sallie

## 🎯 Objective

We aim to predict pupil size (regression) and classify pupil state (normal, constricted, dilated) from neuronal response data.

## 🧪 Methods Explored

- Data cleaning & visualization
- Linear regression
- PCA + regression
- Multi-layer perceptron (MLP)
- R² score achieved: **~0.16**
- MSE: **2,645,379.0**

## ⚠️ Challenges

- NaNs in original data
- Weak performance of linear models
- Nonlinear patterns better captured by MLP, but results still suboptimal

## 📦 Dependencies

Install dependencies with:

```bash
pip install -r requirements.txt
```

## 🧠 Dataset

Allen Brain Observatory dataset (public neuroscience dataset of neural recordings)

> ⚠️ Full dataset not included here. You can request or download from the Allen Brain Atlas portal.

## 📁 File

- `Kaloso_DL_Code_updated.ipynb` – the final project notebook
