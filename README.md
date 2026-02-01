# 🌍 Global Nutrition, Economics & Health Analysis

**Multi-Paradigm ML Project: Classical ML + Deep Learning + Quantum ML**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![ML](https://img.shields.io/badge/ML-XGBoost%20%7C%20TensorFlow%20%7C%20Qiskit-orange)](https://github.com)
[![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://jupyter.org)

## 📌 One-Notebook Analysis

This project performs comprehensive analysis of global nutrition, economic development, and health outcomes **entirely within a single Jupyter notebook** (`MAIN.ipynb`).

## 🎯 Key Features

- **All-in-one analysis**: Complete pipeline from preprocessing to forecasting in single notebook
- **Multi-paradigm ML**: Classical ML, Deep Learning, and Quantum ML comparison
- **Quantum Insights**: Hidden pattern discovery using quantum kernel methods
- **Practical forecasting**: Predictions with uncertainty quantification for 2023-2028
- **SHAP analysis**: Interpretable feature importance for policy decisions

## 📊 Quick Results Summary

| Model | Best R² Score | Key Insight |
|-------|--------------|-------------|
| XGBoost (Full) | 0.9546 | Highest accuracy for undernourishment prediction |
| Quantum Kernel | Hidden patterns in Kuwait's data | Insight Strength: 8.9208 |
| Neural Network | 0.892 | Deep learning benchmark |
| Forecast 2028 | 7.41% undernourishment | 20.1% reduction from 2023 |

## 🚀 Quick Start

### 1. Clone & Setup
```bash
2. Run the Notebook
```bash
jupyter notebook MAIN.ipynb
```

📁 Files Overview
| File | Purpose |
|------|---------|
| `MAIN.ipynb` | Main comprehensive analysis (all code in one place) |
| `final-data.csv` | Processed dataset (1960-2022, 180+ countries) |
| `images/` | Generated quantum insight visualizations |
| `article.md` | Research article/background documentation |
| `prototype2.ipynb` | Development prototype (optional reference) |

i.e - **Quantum Insights**: Hidden pattern discovery using quantum kernel methods
- **Practical forecasting**: Predictions with uncertainty quantification for 2023-2028
- **SHAP analysis**: Interpretable feature importance for policy decisions

## 📊 Quick Results Summary
| Model | Best R² Score | Key Insight |
|-------|--------------|-------------|
| XGBoost (Full) | 0.9546 | Highest accuracy for undernourishment prediction |
| Quantum Kernel | Hidden patterns in Kuwait's data | Insight Strength: 8.9208 |
| Neural Network | 0.892 | Deep learning benchmark |
| Forecast 2028 | 7.41% undernourishment | 20.1% reduction from 2023 |

🏗️ Notebook Structure
The `MAIN.ipynb` notebook contains these complete sections:

**Part 1: Configuration & Setup**
* Library imports and system configuration
* Resource optimization for 8GB RAM systems
* Target variables and feature mapping

**Part 2: Data Preprocessing**
* Loading and cleaning `final-data.csv`
* Handling missing values
* Feature engineering and normalization

**Part 3: Classical Machine Learning**
* Linear models (Regression, Ridge, Lasso)
* Tree-based models (Random Forest, Gradient Boosting)
* XGBoost (Best performer: R²=0.9546)
* Resource vs Full model comparison

**Part 4: Deep Learning**
* Neural network architectures
* Callbacks and training optimization
* Performance benchmarking

**Part 5: Quantum Machine Learning**
* Quantum kernel methods with Qiskit
* Quantum Insight Engine for hidden patterns
* Key finding: Hidden patterns in Kuwait's data (2007-2011)

**Part 6: Model Interpretation**
* SHAP analysis for feature importance
* Uncertainty quantification with prediction intervals
* 90% coverage validation (92.3% achieved)

**Part 7: Forecasting**
* Future projections (2023-2028)
* Ensemble forecasting approach
* Policy implications

**Part 8: Results & Visualization**
* Performance comparison charts
* Quantum insight visualizations
* Comprehensive summary tables

## 📈 Key Findings
1. **Best Model**: XGBoost achieved R²=0.9546 for undernourishment prediction
2. **Top Predictors**: GDP per capita and caloric intake most influential
3. **Quantum Discovery**: Hidden non-linear patterns in Kuwait's stable high-income, high-nutrition profile
4. **Forecast**: 20.1% reduction in undernourishment by 2028 (from 9.27% to 7.41%)
5. **Resource Efficiency**: Resource-constrained models offer 94% accuracy at 50% speed

## 🔬 Technologies Used
* **Data Processing**: Pandas, NumPy, Scikit-learn
* **Classical ML**: XGBoost, Random Forest, Gradient Boosting
* **Deep Learning**: TensorFlow/Keras
* **Quantum ML**: Qiskit (quantum kernels)
* **Visualization**: Matplotlib, Seaborn, SHAP, Plotly
* **Analysis**: SHAP values, uncertainty quantification

## 📚 Data Sources
* Our World in Data: Nutritional and economic indicators
* World Bank: GDP per capita data
* WHO/FAO: Health and nutrition statistics

## 🎮 How to Use the Notebook
1. Run all cells sequentially for complete analysis
2. Skip quantum sections if Qiskit not installed (set `QML_ENABLED = False`)
3. Adjust resource mode for your system (`RESOURCE_MODE = True/False`)
4. Modify target variables in configuration cell for different analyses

## ⚠️ Note on Quantum ML
The quantum ML section demonstrates quantum computing's potential but also shows its limitations for classical datasets. It's included as an exploratory component showing:
* How to implement quantum kernels
* When quantum approaches are/aren't appropriate
* Quantum-inspired insight methods

## 📄 License
MIT License - See included LICENSE file

## 👤 Author
[Your Name] - [Your Contact/LinkedIn/GitHub]

---

This project demonstrates that comprehensive ML analysis can be effectively contained within a single, well-organized notebook while maintaining readability and scientific rigor.
git clone https://github.com/yourusername/global-nutrition-economics-health.git
cd global-nutrition-economics-health
pip install -r requirements.txt

## Essential requirements.txt
```txt
# Core Data Science
numpy==1.23.5
pandas==1.5.3
scikit-learn==1.2.2
scipy==1.10.1

# Machine Learning Models
xgboost==1.7.6
lightgbm==4.1.0

# Deep Learning
tensorflow==2.12.0
keras==2.12.0

# Quantum Computing (Optional - can be skipped)
qiskit==0.43.0
qiskit-machine-learning==0.6.0
qiskit-aer==0.12.0

# Visualization
matplotlib==3.7.1
seaborn==0.12.2
plotly==5.14.1
shap==0.41.0

# Jupyter Environment
jupyter==1.0.0
ipykernel==6.23.1
ipywidgets==8.0.6

# Utilities
tqdm==4.65.0
joblib==1.2.0
```

## 4. Optimized .gitignore
```gitignore
# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
*.egg-info/
.installed.cfg
*.egg

# Jupyter
.ipynb_checkpoints
*.ipynb_checkpoints

# IDE
.vscode/
.idea/
*.swp
*.swo
*~

# Data (optional - comment out if you want to track data)
*.csv
*.h5
*.pkl
*.pickle
*.feather
*.parquet

# OS
.DS_Store
Thumbs.db

# Environment
.env
venv/
env/
ENV/

# Output
output/
models/  # If you don't want to track saved models
```

## 5. Quick Setup Instructions
```bash
# Create repository
mkdir global-nutrition-economics-health
cd global-nutrition-economics-health

# Create minimal folder structure
mkdir images
mkdir notebooks  # Optional for future work

# Move your files (from DATAMINING-CASE folder)
mv ../DATAMINING-CASE/MAIN.ipynb .
mv ../DATAMINING-CASE/final-data.csv .
mv ../DATAMINING-CASE/article.md .
mv ../DATAMINING-CASE/prototype2.ipynb .  # Or notebooks/prototype2.ipynb
mv ../DATAMINING-CASE/*.png images/

# Create essential files
touch README.md requirements.txt .gitignore

# Initialize git
git init
git add .
git commit -m "Initial commit: Global nutrition, economics and health analysis"
git branch -M main
git remote add origin https://github.com/yourusername/global-nutrition-economics-health.git
git push -u origin main
```
