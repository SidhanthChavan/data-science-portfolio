# Sidhanth Chavan — Data Science Portfolio

> MSc Data Science — Manchester Metropolitan University
> Python · PyTorch · Scikit-Learn · SQL · Power BI · Docker · AWS

---

## About Me

Data Science MSc graduate with hands-on experience building end-to-end ML systems — from deepfake detection at 94.7% accuracy on 1M+ videos, to commercial energy cost analysis and agricultural disease classification. Currently expanding into cloud infrastructure and DevOps.

Open to junior roles in data science, cloud support, or technical analysis across UK and Ireland.

**Visa:** UK Graduate Visa — valid to December 2027 (no sponsorship required)

---

## Projects

### Deepfake Detection — EfficientNet-B4 + Attention Fusion
> Multi-stream deep learning system for synthetic video detection

| Metric | Score |
|--------|-------|
| Accuracy | 94.7% |
| AUC | 0.987 |
| Dataset | AV-Deepfake1M — 1M+ videos |

Architecture: EfficientNet-B4 (RGB) + ResNet18 (DCT frequency) + Multi-head self-attention fusion + Grad-CAM interpretability

**Tech:** PyTorch · EfficientNet-B4 · ResNet18 · MTCNN · Grad-CAM · scikit-learn

[View Repository](https://github.com/SidhanthChavan/deepfake-detection-efficientnet)

---

### Rice Leaf Disease Detection — ResNet-18 CNN
> Automated classification of rice leaf diseases for precision agriculture

| Metric | Score |
|--------|-------|
| Accuracy | 92.5% |
| F1-Score | 0.91 |
| Classes | Bacterial leaf blight · Brown spot · Leaf smut |

Architecture: ResNet-18 fine-tuned on ImageNet weights, k-fold cross-validation, ablation study confirming augmentation adds +12.5% accuracy

**Tech:** PyTorch · ResNet-18 · torchvision · scikit-learn · Matplotlib

[View Repository](https://github.com/SidhanthChavan/Rice-Leaf-Disease-Detection)

---

### Commercial Energy Cost Optimisation
> Predictive analysis of non-commodity costs across 80 UK commercial electricity consumers

| Metric | Result |
|--------|--------|
| Polynomial R² | 0.978 |
| Pearson r | 0.97 |
| Key finding | Large consumers pay ~40% more per unit |

Discovered that NCC charges scale non-linearly with consumption — driven by Triad-based TNUoS transmission charging. Fixed charges account for ~47% of a typical bill, setting a hard ceiling on cost reduction strategies.

**Tech:** Python · Pandas · Scikit-Learn · Matplotlib · Seaborn · Power BI

[View Repository](https://github.com/SidhanthChavan/Commercial-Energy-Cost-Optimisation)

---

### UK Car Price Prediction — Machine Learning (Semester 1)
> Regression analysis on 400,000 UK used car listings

| Model | R² | RMSE |
|-------|-----|------|
| Decision Tree | 0.880 | 0.341 |
| KNN | 0.853 | 0.385 |
| Linear Regression | 0.511 | 0.701 |

Compared Linear Regression, KNN, and Decision Tree with GridSearchCV tuning. Decision Tree best model — vehicle age and mileage identified as top predictive features.

**Tech:** Python · Pandas · Scikit-Learn · Matplotlib · Seaborn

---

### UK Car Price Prediction — Advanced ML (Semester 2)
> Stacking ensemble achieving R²=0.94 on same dataset

| Model | R² |
|-------|-----|
| Stacking Ensemble | 0.94 |
| Random Forest baseline | ~0.88 |

Built stacking ensemble (Random Forest + Gradient Boosting + Ridge meta-learner) with RFECV feature selection, SHAP interpretability, PCA + t-SNE dimensionality reduction, and K-Means clustering as feature engineering.

**Tech:** Python · Scikit-Learn · SHAP · Tableau · Pandas

---

## Skills

| Category | Tools |
|----------|-------|
| Languages | Python · SQL · Bash |
| Deep Learning | PyTorch · EfficientNet · ResNet · MTCNN · Grad-CAM |
| ML | Scikit-Learn · XGBoost · Random Forest · Ensemble Methods · SHAP |
| Data | Pandas · NumPy · Matplotlib · Seaborn · Plotly · Power BI · Tableau |
| MLOps | Docker · Jenkins · Git · CI/CD |
| Cloud | AWS (fundamentals) · Linux (active learning) |

---

## Contact

linkedin.com/in/sidhanth-chavan
github.com/SidhanthChavan
sidcvn001@gmail.com
Manchester, UK
