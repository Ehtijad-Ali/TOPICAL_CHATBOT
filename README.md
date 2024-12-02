# 🤖 Topical Chatbot  

## 🎯 Objective  
To build a machine learning-powered chatbot capable of understanding and generating contextually accurate responses based on a topical dataset.  

## 📝 Brief Description  
This project demonstrates the implementation of a chatbot using deep learning and natural language processing (NLP) techniques. The chatbot is trained on the **Enriched Topical Chat Dataset**, which provides diverse conversational data.  

### ✨ Features:  
- ⚙️ **Data preprocessing** and tokenization using **spaCy**.  
- 📏 Sequence padding for uniform input to the model.  
- 🧠 Deep learning model with **embedding layers**, **LSTMs**, and dense layers for context-based generation.  
- 📊 Performance visualization with training and validation metrics.  

### 🛠️ Dependencies  
- 🐍 Python  
- 🧵 TensorFlow/Keras  
- 🤗 Transformers  
- 🧠 spaCy  
- 📈 Matplotlib  
- 🧮 Pandas  

## 🚀 Usage  
You can access and execute the project using Google Colab by clicking the badge below:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/asadnazir14/Topical-_Chatbot/blob/main/Topical_Chatbot.ipynb)  

## 📂 Dataset  
The project uses the **Enriched Topical Chat Dataset**, which can be downloaded as follows:  
```bash  
!wget https://enriched-topical-chat.s3.amazonaws.com/train.json  
!wget https://enriched-topical-chat.s3.amazonaws.com/valid_freq.json  
!wget https://enriched-topical-chat.s3.amazonaws.com/valid_rare.json  
!wget https://enriched-topical-chat.s3.amazonaws.com/test_freq.json  
!wget https://enriched-topical-chat.s3.amazonaws.com/test_rare.json  
```  

## 📊 Results  
- ✅ The chatbot shows improved performance over epochs with increasing accuracy and decreasing loss.  
- 📈 Training and validation metrics are visualized to evaluate the model's performance.  

## 🏁 Conclusion  
This project highlights the application of NLP and deep learning in building a contextually aware chatbot. Future improvements can include fine-tuning the model, integrating pre-trained transformers, and deploying the chatbot for real-world use cases.  
