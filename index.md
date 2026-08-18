# Portfolio

---
## Skills & Tools

### Machine Learning & AI
- Deep Learning (CNNs, RNNs, LSTMs, Transformers)
- Computer Vision (Segmentation, Object Detection)
- NLP (BERT, Tokenization, Attention Models)
- Time‑Series Forecasting (ARIMA, Prophet, LSTM)
- Classical ML (Regression, Classification, Clustering)

### Data Engineering
- PySpark, Delta Lake, Databricks
- ETL Pipelines, Data Cleaning, Feature Engineering
- Distributed Computing

### Programming & Tools
- Python, SQL, Git, Docker
- PyTorch, TensorFlow, Scikit‑learn
- Jupyter, Colab, FastAPI, Streamlit
- AWS, Azure

---

# Featured Projects in Machine Learning, Data Science & NLP

---

## Tumour Detection & Segmentation in MRI Scans (UW‑Madison Dataset)

I designed and trained a custom encoder–decoder segmentation model to identify tumour regions in MRI scans. The project explores the full pipeline: preprocessing, augmentation, mask generation, model training, and evaluation. The model produces pixel‑level segmentation maps, helping clinicians quickly identify abnormal regions.

<br>
<img src="images/Tumor.jpeg?raw=true" style="width:25%;"/>
<br>

**Highlights**
- Worked with complex medical imaging data  
- Built custom CNN segmentation architecture  
- Evaluated using Dice Score & IoU  
- Demonstrated strong PyTorch engineering  

**Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)

**[View code on Kaggle](https://www.kaggle.com/code/ollatunji/tumor-detection-in-mri-scans-v2)**

---

## Gravitational Wave Analysis & Detection (G2NET Dataset)

I implemented a pipeline that converts raw waveforms into Constant‑Q Transform spectrograms using `nnAudio`, then trained a deep‑learning classifier to distinguish real gravitational wave events from noise.

<br>
<img src="images/Wave.jpeg" style="width:25%;"/>
<br>

**Highlights**
- Signal processing + deep learning  
- Spectrogram feature engineering  
- PyTorch training pipeline  
- Scientific dataset handling

 **Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)

**[View code on Kaggle](https://www.kaggle.com/code/ollatunji/gravitational-wave-analysis-and-detection)**

---

## Bitcoin Price Movement Prediction (LSTM Models)

I built two LSTM‑based neural networks:  
1. A regression model predicting next‑day closing price  
2. A classification model predicting rise/fall probability  

<br>
<img src="images/Bitcoin.jpeg" style="width:25%;"/>
<br>

**Highlights**
- Strong time‑series modelling  
- Regression vs classification comparison  
- LSTM architecture design  
- Financial dataset feature engineering

**Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)

**[View code on Kaggle](https://www.kaggle.com/code/ollatunji/daily-btc-usd-stock-prediction-with-lstms-358b73)**

---

## Customer Churn Prediction (Telecom Dataset)

I built a churn‑prediction model using Logistic Regression, Random Forest, and XGBoost to identify customers likely to leave a telecom service. The project includes feature engineering, class‑imbalance handling, and explainability using SHAP.

**Highlights**
- Real business problem  
- ROC‑AUC, Recall, Precision  
- SHAP explainability  
- Imbalanced dataset handling

**Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Scikit--learn-white?logo=scikitlearn)](#)
[![](https://img.shields.io/badge/SHAP-white?logo=python)](#) 


---

## Credit Card Fraud Detection (Anomaly Detection)

I developed a fraud‑detection pipeline using SMOTE, PCA, and ensemble models to detect rare fraudulent transactions with high precision.

**Highlights**
- Anomaly detection expertise  
- Precision‑focused evaluation  
- PCA dimensionality reduction  
- Robust ML pipeline design  

**Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Scikit--learn-white?logo=scikitlearn)](#)
[![](https://img.shields.io/badge/XGBoost-white?logo=xgboost)](#)


---

## Retail Demand Forecasting (Time Series)

I compared ARIMA, Prophet, and LSTM models to predict product demand, analysing seasonality, trends, and noise.

**Highlights**
- Time‑series forecasting  
- Classical vs deep‑learning comparison  
- MAPE & RMSE evaluation  
- Business‑focused interpretation  

**Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Prophet-white?logo=python)](#)
[![](https://img.shields.io/badge/TensorFlow-white?logo=tensorflow)](#)


---

## Sentiment Analysis with BERT (NLP)

I fine‑tuned a BERT model to classify sentiment in product reviews, covering tokenization, attention mechanisms, training optimisation, and evaluation.

**Highlights**
- Transformer models  
- Attention‑based NLP  
- Large‑scale text processing  
- HuggingFace ecosystem  

**Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)
[![](https://img.shields.io/badge/HuggingFace-white?logo=huggingface)](#)

**[View code on Kaggle](https://www.kaggle.com/code/ollatunji/nlp-sentiment-analysis)**

---

## YOLOv8 Object Detection (Computer Vision)

I trained a YOLOv8 model on a custom dataset to detect objects with high accuracy, including annotation, augmentation, training, and inference visualisation.

**Highlights**
- State‑of‑the‑art CV  
- Custom dataset annotation  
- IoU & mAP evaluation  
- Real‑time inference  

**Tech Stack**  
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/YOLOv8-white?logo=yolo)](#)
[![](https://img.shields.io/badge/OpenCV-white?logo=opencv)](#)


---

## End‑to‑End Data Pipeline (PySpark + Delta Lake)

I built a scalable ETL pipeline using PySpark to ingest, clean, transform, and store data in Delta Lake. The pipeline supports incremental loads, schema evolution, and efficient querying.

**Highlights**
- Distributed computing  
- Delta Lake architecture  
- Production‑ready ETL  
- Databricks engineering  

**Tech Stack**  
[![](https://img.shields.io/badge/PySpark-white?logo=apachespark)](#)
[![](https://img.shields.io/badge/Delta--Lake-white?logo=databricks)](#)
[![](https://img.shields.io/badge/Databricks-white?logo=databricks)](#)


---

# Featured Projects in Software Development

- **Translation App** — Real‑time language translation  
- **Weather App** — Live weather updates  
- **Blog App** — Full CRUD blog platform  
- **E‑commerce App** — Django store with Stripe payments  
- **Social Media App (Cruddur)** — AWS‑powered microblogging platform  

---

# Why Hire Me

I bring a combination of strong machine‑learning expertise, practical engineering skills, and the ability to communicate complex ideas clearly. I build models that work in production, not just notebooks. I’m comfortable with ambiguity, fast learning, and delivering results under pressure.

I’m passionate about solving real problems with data — and I’m always improving.

---
