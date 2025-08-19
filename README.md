# 🎬 IMDB Movie Review Sentiment Analyzer  
[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)  
[![PyTorch](https://img.shields.io/badge/Deep%20Learning-PyTorch-red?logo=pytorch)](https://pytorch.org/)  
[![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-brightgreen?logo=streamlit)](https://streamlit.io/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

---

## 📌 Overview  

The **IMDB Sentiment Analyzer** is an **End-to-End Deep Learning Pipeline** that classifies IMDB movie reviews into **Positive** or **Negative** sentiments.  
It uses an **LSTM neural network built in PyTorch** and is deployed with an **interactive Streamlit web app**.  

💡 Just enter any movie review, and the app will display:  
- Sentiment result (**Positive/Negative**)  
- Confidence score visualized as ⭐ star ratings  

---

## 🔗 Live Demo  
👉 [Streamlit App](https://your-deployment-link.streamlit.app/)  

---

## 📽️ UI Preview  

| ![](assets/ui1.png) | ![](assets/ui2.png) |

---

## 🚀 Features  

- 🧠 **Deep Learning Model** – LSTM trained from scratch  
- 🗃 **IMDB Dataset (50K reviews)**  
- 🎨 **Streamlit UI** with custom background & styled theme  
- ⭐ **Confidence visualization with star ratings**  
- 📊 **~87% Accuracy on test dataset**  

---

## 🏗️ Architecture  

1. **Data Preprocessing** (cleaning, tokenization, encoding)  
2. **Vocabulary Encoding**  
3. **Train/Test Split**  
4. **Model Training (LSTM)**  
5. **Save Trained Model (`imdb_lstm_model.pth`)**  
6. **Deploy using Streamlit**  

**Model Summary:**  
- Embedding Layer  
- LSTM Layer  
- Dropout (0.5)  
- Fully Connected Layer  
- Sigmoid Output  

---

## 📂 Dataset  

Dataset: [IMDB 50K Movie Reviews](https://ai.stanford.edu/~amaas/data/sentiment/)  
- 25,000 labeled reviews for training  
- 25,000 labeled reviews for testing  
- Balanced Positive & Negative classes  

---

## 🛠️ Tech Stack  

- **Python 3.9+**  
- **PyTorch** (Deep Learning)  
- **Streamlit** (Web UI)  
- **Pandas, NumPy, Scikit-learn** (Data Processing)  

---

## ⚙️ Installation & Setup  

### 1. Clone the Repository  
```bash
git clone https://github.com/your-username/IMDB-Sentiment-Analyzer.git
cd IMDB-Sentiment-Analyzer
```

### 2. Create Virtual Environment & Install Dependencies  
```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

pip install -r requirements.txt
```

### 3. Run Streamlit App  
```bash
streamlit run app.py
```

---

## 📊 Results  

- Accuracy: **~87%**  
- Confidence score visualization helps interpret predictions easily.  

---

## 🔮 Future Enhancements  

- ✅ Add Transformer/BERT-based model for better accuracy  
- ✅ Deploy with Docker for scalability  
- ✅ Multi-language support  

---

## 📜 License  

This project is licensed under the **MIT License** – see the LICENSE file for details.  

---
