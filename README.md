# Sales Forecasting & Optimization System  
**Graduation Project for IBM AI & Data Science (DEPI)**  


---
## 📽 Demos

- 🌐 **Live Streamlit App**: [Sales Forecasting Streamlit](https://depi-sales-prediction-app.streamlit.app/)  
- 🌐 **Live Flask App**: [Sales Forecasting Flask](https://confident-goldy-vmrmuhvmedd-ff7926b4.koyeb.app/)  

---

## 🌟 Key Features  

### 🔮 Intelligent Forecasting System  
- Automated prediction engine  
- Self-optimizing algorithms that improve over time  
- Real-time demand planning capabilities  
- Smart parameter configuration system  

### 🖥️ Business Applications  
1. **Enterprise Forecasting Application** - Production-ready web service  
2. **Executive Dashboard** - Intuitive business intelligence portal  
3. **Analytics Workbench** - Interactive data exploration suite  

### 📦 Data Foundation  
- Automated data processing pipelines  
- Advanced pattern recognition systems  
- Multi-source data integration  
- Automatic anomaly detection  

---

## 🛠 Technical Stack  

| Component       | Technologies Used                          |
|-----------------|--------------------------------------------|
| Core ML         | Python 3.10, Scikit-learn, TensorFlow 2.12 |
| Forecasting     | Prophet, Statsmodels, XGBoost              |
| Visualization   | Plotly, Dash, Streamlit, Altair            |
| Infrastructure  | Flask, Docker, Redis, Celery               |
| Optimization    | Optuna, OR-Tools, PuLP                     |

---

## 📂 Project Structure  

```plaintext
Sales-Forecasting-Optimization/
├── data/                       
│   ├── output.csv                  
│   └── stores_sales_forecasting.csv
│
├── notebooks/                
│   └── forecasting_model.ipynb
│   
│
├── flask_app/                
│   ├── app.py
│   ├── best_model.pkl
│   ├── features_columns.pkl
│   ├── README.md  
│   ├── requirements.txt
│   ├── .env
│   ├── static/
│   │   └── styles.css
│   └── templates/
│        ├── index.html
│        └── documentation.html               
│
├── streamlit_app/              
│   ├── app.py                   
│   ├── best_model.pkl           
│   ├── features_columns.pkl     
│   ├── requirements.txt         
│   └── README.md                                 
│
├── dashboard/                  
│   ├── dashboard_app.ipynb      
│   ├── cleaned_data.csv
│   └── README.md                 
│
├── models/                    
│   ├── best_model.pkl          
│   └── feature_encoder.pkl     
│
├── README.md  
└── requirements.txt
```


## 🚀 Installation & Deployment
1. Clone Repository
```bash
   git clone https://github.com/yourusername/Sales-Forecasting-Optimization.git
   cd Sales-Forecasting-Optimization
```

2. Initialize Virtual Environment
```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
```
3. Install Dependencies
```bash
   pip install -r requirements.txt
```

## 💻 System Operation
🧪 Start Jupyter Lab (Development)
```bash
   jupyter lab --port=8888 --no-browser
```

🌐 Launch Production API
```bash
   cd flask_app
   gunicorn --workers=4 --bind 0.0.0.0:5000 app:app
```

Access API Docs: **`http://localhost:5000/api/docs`**

📈 Start Business Dashboard
```bash
   cd streamlit_app
   streamlit run app.py --server.port 8501
```
📊 Launch Analytics Dashboard
```bash
   cd dashboard
   python dashboard_app.py
```























