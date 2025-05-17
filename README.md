# PCE Prediction Using Machine Learning

This project aims to predict the Power Conversion Efficiency (PCE) of photovoltaic materials using machine learning regression models. PCE is a key metric used to evaluate the performance of solar cell materials, and this predictive model assists in identifying high-efficiency candidates based on their physical and chemical properties.

## 🚀 Project Overview

We use a dataset containing material features such as:

- Thickness (`thickness`)
- Band gap (`band_gap`)
- Electron affinity (`electron_affinity`)
- Doping concentration (`doping`)
- Defect density (`defect`)

The target variable is:
- **PCE**: Power Conversion Efficiency (as a percentage)

## 🧠 ML Approach

- **Data Preprocessing**: 
  - Handling missing values
  - Log transformations for skewed features (e.g., `log_doping`, `log_defect`)
  - Feature scaling (if needed)
- **Exploratory Data Analysis**:
  - Distributions and pairwise relationships
  - Correlation analysis
- **Modeling**:
  - Random Forest Regression
  - K-Fold Cross-Validation
  - Evaluation using RMSE and R² score
- **Model Interpretation**:
  - Feature importance plots
  - Partial dependence plots

## 🔍 Results

- **Best Model**: Random Forest Regressor
- **Cross-Validated R² Score**: ~0.98+
- **RMSE**: ~0.32
- Very small difference with/without log transformations

## 📁 Project Structure

## 🧪 Dependencies

- Python 3.12
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- jupyter

Install them using:

```bash
pip install -r requirements.txt
```
```bash
jupyter notebook notebooks/pce_prediction.ipynb
```

## 📜 License
This project is licensed under the MIT License.

## ✍️ Author
**Md Taufique Hasan**  
📧 Email: [taufiquehr@gmail.com]  
🔗 GitHub: [github.com/taufique01](https://github.com/taufique01)  
🔬 Passionate about AI/ML driven analysis and application development


