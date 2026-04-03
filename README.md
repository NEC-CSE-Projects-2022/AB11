# 🌱 Climate-Smart Cotton Yield Prediction using LightGBM

---

## 👥 Team Info

### 22471A05XX — Satuluri Mohammad Sakhib  
🔗 LinkedIn  
**Work Done:**  
- Implemented LightGBM and Random Forest models  
- Developed preprocessing pipeline (encoding, outlier removal)  
- Performed model training, evaluation, and analysis  
- Integrated full ML workflow and documentation  

---

### 22471A05XX — Name  
🔗 LinkedIn  
**Work Done:**  
- Dataset collection and preparation  
- Synthetic data generation using bootstrapping  
- Feature engineering  

---

### 22471A05XX — Name  
🔗 LinkedIn  
**Work Done:**  
- Exploratory Data Analysis (EDA)  
- Data visualization and plotting  
- Performance evaluation  

---

### 22471A05XX — Name  
🔗 LinkedIn  
**Work Done:**  
- Frontend/backend integration  
- Deployment setup  
- Documentation  

---

## 📄 Abstract

This project focuses on predicting cotton yield using climate-smart machine learning techniques. The system uses key features such as accumulated heat, soil type, cultivar, and fertilizer application to estimate yield accurately.

Two ensemble models—Random Forest and LightGBM—are implemented and compared. LightGBM outperforms Random Forest due to its efficient gradient boosting mechanism. The model achieves approximately **99% accuracy**, making it suitable for precision agriculture and decision support systems.

---

## 📑 Paper Reference (Inspiration)

👉 *Climate-Smart Cotton Yield Prediction: A Comparative Study of Random Forest and LightGBM*  
📌 IEEE Conference (ICIH 2025)

---

## 🚀 Our Improvements

- Enhanced dataset using synthetic data generation  
- Improved preprocessing (outlier removal + feature engineering)  
- Hyperparameter tuning for higher accuracy  
- Built scalable ML pipeline  
- Prepared system for real-world deployment  

---

## 📌 About the Project

### 🔹 What it does
- Predicts cotton yield using ML models  
- Supports regression and classification  

### 🔹 Why it is useful
- Helps farmers make better decisions  
- Optimizes fertilizer and irrigation  
- Supports climate-smart agriculture  

### 🔹 Workflow  
Input Data → Preprocessing → Feature Engineering → Model Training → Prediction Output  

---

## 📊 Dataset Used

👉 Cotton Yield Dataset (Synthetic + Historical Inspired)

### Details:
- ~64,000 samples  
- 11 features  
- Includes:
  - Accumulated heat  
  - Soil type  
  - Cultivar  
  - Fertilizer usage  

- Synthetic data used for balancing and performance improvement  

---

## ⚙️ Dependencies

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- LightGBM  
- Matplotlib  
- Seaborn  

---

## 📈 EDA & Preprocessing

- Handled missing values  
- Removed outliers  
- Label encoding for categorical features  
- Balanced dataset using synthetic data  
- Visualized distributions  

---

## 🤖 Model Training

### Models Used:
- Random Forest Regressor  
- LightGBM Regressor (Primary Model)

### Training Setup:
- Train-Test Split: 80:20  
- Cross-validation  
- Hyperparameter tuning  

---

## 🧪 Evaluation Metrics

- RMSE (Root Mean Square Error)  
- R² Score  
- NSE (Nash-Sutcliffe Efficiency)  

---

## 📊 Results

| Model          | R² Score | RMSE  |
|---------------|---------|-------|
| Random Forest | 0.979   | 4.668 |
| LightGBM      | **0.993** | **2.711** |

✅ LightGBM performs best due to efficient boosting and handling of nonlinear data.

---

## ⚠️ Limitations

- Depends on synthetic data  
- Limited real-time inputs  
- Region-specific dataset  

---

## 🔮 Future Work

- Integrate real-time weather APIs  
- Use satellite data  
- Expand dataset  
- Build web/mobile app  

---

## 🌐 Deployment

- Trained on Google Colab (GPU)  
- Can be deployed using Flask/Django  
- Suitable for web/mobile integration  
- Future scope: IoT-based smart farming  

---

