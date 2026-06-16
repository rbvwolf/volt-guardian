# Volt Guardian XAI
Volt-Guardian XAI is an Explainable AI (XAI) project designed to monitor and predict the State of Health (SoH) for Electric Vehicle batteries. This project was developed as part of the 3rd Year Computer Engineering curriculum.

The project combines:

- Genetic Algorithm (GA) Hyperparameter Optimization
- XGBoost Regression
- SHAP (SHapley Additive exPlanations)
- Feature Engineering
- Comparative Model Benchmarking

The primary objective is not only to predict battery degradation with high accuracy but also to provide transparent explanations for each prediction.

---

## Key Features

### Hybrid GA-XGBoost Architecture

A Genetic Algorithm is used to optimize XGBoost hyperparameters automatically, resulting in improved predictive performance.

### Explainable AI (XAI)

SHAP is integrated to:

- Explain global feature importance
- Analyze local predictions
- Generate waterfall and beeswarm visualizations
- Increase model transparency

### Advanced Feature Engineering

The framework introduces custom battery stress indicators:

- Thermal Stress Index
- Monthly Charge Intensity
- Power Stress

These engineered features help the model better capture battery degradation behavior.

---

## Dataset

The dataset contains EV battery operational parameters such as:

- Battery Capacity
- Vehicle Age
- Charging Cycles
- Fast Charging Ratio
- Average Temperature
- Internal Resistance
- Driving Style
- Battery Chemistry

Target Variable:

```text
State of Health (SoH %)
```

---

## Model Performance

### GA-XGBoost (Champion Model)

| Metric | Score |
|----------|----------|
| R² | 0.9891 |
| Adjusted R² | 0.9890 |
| MAE | 0.2650 |
| RMSE | 0.3404 |
| MAPE | 0.28% |

### Cross Validation

| Metric | Value |
|----------|----------|
| Mean R² | 98.83% |
| R² Std | ±0.08 |
| Mean MAE | 0.27 |
| MAE Std | ±0.01 |

---

## Model Comparison

The framework evaluates multiple machine learning models:

1. GA-XGBoost (Hybrid Champion)
2. Random Forest
3. Standard XGBoost
4. Gradient Boosting
5. Decision Tree
6. Linear Regression

GA-XGBoost achieved the best overall performance.

---

## Explainability Visualizations

The project generates:

- SHAP Global Beeswarm Plot
- SHAP Waterfall Plot
- Actual vs Predicted Analysis
- Residual Distribution Analysis
- Feature Correlation Heatmap

These visualizations help researchers understand the decision-making process of the model.

---

## Technologies Used

- Python
- XGBoost
- SHAP
- Scikit-Learn
- sklearn-genetic-opt
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Future Work

- Real-time EV battery monitoring
- Web-based dashboard deployment
- Integration with Battery Management Systems (BMS)
- Deep Learning based SoH estimation
- Edge AI deployment for embedded systems

---

# Türkçe

## Volt-Guardian XAI

Volt-Guardian XAI, elektrikli araç (EV) bataryalarının Sağlık Durumu (State of Health - SoH) tahmini ve yorumlanması amacıyla geliştirilmiş bir Açıklanabilir Yapay Zeka (XAI) sistemidir.

Bu proje;

- Genetik Algoritma (GA)
- XGBoost
- SHAP
- Özellik Mühendisliği
- Model Karşılaştırma Analizleri

yaklaşımlarını bir araya getirerek yüksek doğrulukta tahminler üretmektedir.

### Öne Çıkan Özellikler

- Hibrit GA-XGBoost mimarisi
- SHAP tabanlı açıklanabilir yapay zeka
- Gelişmiş özellik mühendisliği
- Çoklu model karşılaştırmaları
- Akademik düzeyde performans değerlendirmesi

### Performans

- R²: 0.9891
- MAE: 0.2650
- RMSE: 0.3404
- MAPE: %0.28

### Kullanılan Teknolojiler

- Python
- XGBoost
- SHAP
- Scikit-Learn
- sklearn-genetic-opt
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Contributors

| Name |
|--------|
| Eren OĞAN | 
| Enes GÜZEL | 
| Esengül VELET |
| Yiğit Mert YILMAZ | 


---

## Citation

If you use this work in academic research, please cite the associated publication and repository.

---

**Volt-Guardian XAI — Making EV Battery Intelligence Explainable**
