![farmer](farmer_in_a_field.jpg)

# 🌱 Crop Prediction using Logistic Regression

This project applies **Logistic Regression** to predict suitable crops based on soil nutrient values and pH levels.  
It demonstrates **data preprocessing, feature scaling, model training, evaluation, and feature-wise performance analysis**.  


## 📊 Dataset

The dataset (`soil_measure.csv`) contains soil features:

- **N** → Nitrogen content  
- **P** → Phosphorus content  
- **K** → Potassium content  
- **pH** → Soil pH value  
- **crop** → Target crop label (classification target)  

---

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/<muhammadrehanazam>/Crop_prediction_Model.git
cd crop-prediction

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
jupyter notebook notebooks/crop_prediction.ipynb
