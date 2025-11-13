# 🛣️ Traffic Accident Prediction System  

This project predicts the **probability of a road accident being severe** based on factors such as weather, speed limit, road type, lighting, and more. It uses a **Random Forest Classifier** trained on traffic and environmental data, and includes a **Streamlit web interface** for interactive predictions.  

---

## 🚀 Features  
✅ Predicts accident severity probability using trained ML model  
✅ Handles missing values and categorical encoding automatically  
✅ Saves and reuses trained models (`.pkl` files) for fast inference  
✅ Easy-to-use web app built with **Streamlit**  
✅ Scalable — can be trained on new datasets  

---

## 🧠 Tech Stack  
- **Python 3.9+**  
- **Streamlit** — UI for prediction  
- **Pandas**, **NumPy** — data manipulation  
- **Scikit-learn** — model training & evaluation  
- **Joblib** — saving/loading models  
- **Matplotlib**, **Seaborn** — visualization  
    

---
## 📊 Dataset Used

**Dataset Name:** Road_Accidents_Safety_Data.csv  
**Source:** [UK Government Open Data Portal](https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data)  

**Rows:** 1,50,000+ (varies slightly per year)  
**Columns:** 32  


**Description:**  
This dataset contains detailed information about road accidents in the UK, including environmental conditions, speed limits, road types, and light/weather conditions. It is widely used for research and predictive modeling of accident risk and severity.

---

## ⚙️ Installation  

1️⃣ **Clone the repository or download ZIP:**  
```bash
git clone https://github.com/Saranyavellanki/Traffic-accident-prediction-
cd Traffic-accident-prediction-
```

2️⃣**Install dependencies:**  
```bash
pip install -r requirements.txt
```
###  Train the Model

Run the following command to train the model and save the necessary files (`.pkl`):

```bash
python train_model.py


