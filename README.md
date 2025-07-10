# 📊 Real-Time Social Media Analytics Dashboard

This project implements a **real-time social media analytics system** using **Apache Spark**, **NLTK (VADER)**, and **Streamlit** to visualize sentiment analysis on user-generated text.

## 🚀 Live App  
🔗 [Click here to open the live Streamlit app](#) *(if deployed)*

## 🧠 Features  
- 📁 Upload your own CSV file with social media comments  
- 🧹 Text cleaning (lowercasing, punctuation removal)  
- 💬 Sentiment classification using VADER (NLTK)  
- 📊 Sentiment distribution chart  
- ☁️ Word cloud of most common words  
- 🔑 Top 10 keywords bar chart  

## 🛠 How to Use  
1. Visit the Streamlit app (or run locally).  
2. Click **Browse files** and upload a CSV file with the following columns:  
   - `Text` – original post/comment  
   - `clean_text` – preprocessed version of the post  
   - `sentiment` – sentiment label: positive, neutral, or negative  
3. View instant insights and visualizations.

## 🧪 Example Dataset  
You can use the included **`ready_for_streamlit.csv`** for testing, or upload your own dataset after processing.

## 📂 Project Structure
├── dashboard.py                 # Streamlit frontend app  
├── flask_mongo_api.py          # Flask backend for MongoDB  
├── kafka_producer.py           # Kafka producer script  
├── spark_streaming.py          # Spark consumer for real-time analysis  
├── requirements.txt            # Required Python packages  
├── ready_for_streamlit.csv     # Sample dataset  
├── .github/workflows           # CI/CD configs  
├── static/, templates/         # Frontend assets for Flask dashboard  


## 🧰 Tools Used  
- 🟩 Google Colab – for preprocessing & sentiment scoring  
- 🔥 Apache Spark (PySpark) – for streaming data processing  
- 🧠 NLTK (VADER) – for sentiment analysis  
- 🧪 Streamlit – to create the user-facing analytics dashboard  
- 🧱 MongoDB – to persist processed sentiment data  
- 📦 Kafka – real-time data producer/consumer pipeline  
- ☁️ GitHub + Streamlit Cloud / Railway – cloud deployment platforms

## 👩‍💻 Authors  
- **Reem Ramadan**  
- **Mena Osman**  
- **Mariam Eslam**  
- **Nayera Ibrahime**  
- **Mariam Mostafa**  
- **Yomna Refaat**  

Biomedical Informatics – Galala University 
