# 🤖 Customer Support System

An AI-powered chatbot for handling customer support queries efficiently using Natural Language Processing (NLP). This system automates responses, classifies user intents, and helps streamline customer service operations.

## 🔧 Features

- Automated customer query handling
- Intent classification using NLP
- Pre-trained model support
- Easy-to-modify logic for custom queries
- Can be integrated into web interfaces

## 📁 Project Structure

Customer-Support-System/ ├── data/ # Sample training data ├── models/ # Trained NLP models ├── app.py # Main application file ├── chatbot.py # Core chatbot logic ├── requirements.txt # Project dependencies └── README.md # Project documentation

conda create -p env python=3.10 -y
conda activate env
uvicorn main:app --reload --port 8001