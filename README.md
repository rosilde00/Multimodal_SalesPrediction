# 🧠 Multimodal Sales Prediction

![Deep Learning](https://img.shields.io/badge/Deep%20Learning-AI-blue)
![Multimodal](https://img.shields.io/badge/Multimodal%20AI-Sales%20Prediction-%2300bfff?logo=automattic&logoColor=white)
![Vision Transformer](https://img.shields.io/badge/Vision_Transformer-ViT-orange?logo=tensorflow)
![DistilBERT](https://img.shields.io/badge/Text-DisilBERT-blue?logo=huggingface)
![PyTorch](https://img.shields.io/badge/PyTorch-red?logo=pytorch&logoColor=white)

**Modello multimodale per la predizione delle vendite con dati tabulari, immagini e descrizioni testuali**

Questo progetto nasce come tesi magistrale e affronta un problema reale: **migliorare l’accuratezza della predizione delle vendite nel settore retail di abbigliamento** integrando informazioni provenienti da diverse modalità — **dati tabulari**, **immagini dei prodotti** e **descrizioni testuali**.

Il lavoro è stato svolto in collaborazione con **ORS GROUP** (ora deda.ai), azienda italiana specializzata in soluzioni di ottimizzazione e automazione tramite algoritmi di AI, Machine Learning e Big Data.

---

## 🚀 Obiettivo del progetto  
Le predizioni di vendita tradizionali si basano principalmente su dati tabulari.  
La domanda alla base del progetto è:

👉 **Possiamo migliorare la predizione includendo informazioni visive e testuali?**

Il caso di studio è l’azienda **Mauli**, produttrice di abbigliamento per bambini, che aveva difficoltà nel definire le quantità da acquistare e nell’allocazione ai punti vendita.

✅ Il modello multimodale sviluppato migliora sensibilmente le performance rispetto a un modello basato solo su dati tabulari.

---

## 🧩 Architettura del modello

Il sistema elabora **tre tipologie di input**:

### 🖼️ 1. Immagini dei prodotti  
- Elaborate tramite **Vision Transformer (ViT)**  
- Produzione di embedding visivi ad alta espressività

### 📝 2. Descrizioni testuali  
- Processate tramite **DistilBERT**  
- Estrazione di embedding semantici del prodotto

### 📊 3. Dati tabulari  
- Storico vendite  
- Metadati del prodotto  
- Variabili gestionali

Gli embedding provenienti dalle tre fonti vengono **concatenati** e passati a una **rete feed-forward** che stima la quantità prevista di vendite.

---

## 🧪 Risultati e metriche  
Il modello multimodale ha mostrato:  
✅ **Riduzione dell’errore** rispetto al baseline tabulare  
✅ **Maggiore robustezza** grazie a informazioni complementari  
✅ **Migliore generalizzazione** su prodotti con poche vendite storiche  

---

## 🛠️ Tecnologie utilizzate

- **PyTorch**  
- **Hugging Face Transformers**  
- **Vision Transformer (ViT)**  
- **Python 3.9+**  
- **Jupyter Notebook**

---

## 📚 Documentazione

Ulteriori dettagli teorici e sperimentali sono disponibili nella [tesi magistrale associata al progetto](https://unitesi.uniupo.it/bitstream/20.500.14238/2545/1/Tesi%20Magistrale%20Garavoglia%20%282%29.pdf).

## 📬 Contatti 

📩 Email: [rosildegaravoglia@gmail.com](mailto:rosildegaravoglia@gmail.com)  
💼 LinkedIn: [Profilo LinkedIn](https://www.linkedin.com/in/rosilde-garavoglia-418858273/)
