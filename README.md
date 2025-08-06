# Predicting Mouse Pupil Size from Neuronal Response

This project was developed as part of the TReND-CaMinA 2025 summer school to use neural recordings to predict pupil size in mice using machine learning techniques.

## 👥 Contributors

- [@Kaloso11](https://github.com/Kaloso11)
- [@championLumamba](https://github.com/Champ-law)
- [@RonaldOuma](https://github.com/OmoRonald)
- [@FarhanahSallie](https://github.com/farhanahsallie)

## 🎯 Objective

To predict pupil size (regression) and classify pupil state (normal, constricted, dilated) from neuronal response data, and evaluate model performance.

## 🧪 Methods Explored

We implemented and compared three different models:

- **Linear Regression** → R² ≈ 22.2%
- **MLP Regressor** → R² ≈ 59.6%
- **Deep Neural Network (DNN)** → R² ≈ 75.0%

## 📊 Results

- Best performance achieved by DNN: **R² = 0.75, RMSE ≈ 3.82%**
- All models used interpolated, preprocessed neural recordings
- The dataset is from the **Allen Brain Observatory**

## ⚙️ Applications

- Neurological disorder detection (e.g. Parkinson’s, Alzheimer’s, ADHD)
- Mental effort and cognitive load tracking
- Emotion and arousal monitoring
- Adaptive interfaces and assistive tech

## 📦 Dependencies

Install dependencies with:

```bash
pip install -r requirements.txt
```

## 📁 Files

- `pupil_prediction_three_models.ipynb` – main notebook covering all models

## 🖥️ Presentation Slides

View the full presentation here:  
🔗 [SynapTech-TReND Final Presentation (Google Drive)](https://docs.google.com/presentation/d/17WXf6x3x9fgKX6iLqIeMMej8pcCnVz8K/edit?usp=sharing&ouid=112125122265751138194&rtpof=true&sd=true)

## 📄 Dataset

Allen Brain Observatory (public)

> ⚠️ Full dataset not included. Download from the Allen Brain Atlas portal.
