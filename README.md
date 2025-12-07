README — Next Word Prediction Using LSTM (with Streamlit Deployment)
🔹 Project Title

Next Word Prediction Using LSTM

🔹 Project Overview

This project focuses on building a deep learning model that predicts the next word in a sentence using Long Short-Term Memory (LSTM) networks. The model is trained on the text of Shakespeare’s Hamlet, a linguistically rich dataset ideal for evaluating sequence learning and contextual understanding. A Streamlit web application is developed for real-time user interaction.

🚀 Key Features

Predicts the next likely word based on input text.

Uses sequence modeling and context learning with LSTM.

End-to-end pipeline from dataset → preprocessing → training → evaluation → deployment.

Interactive Streamlit UI for real-time predictions.

📂 Project Workflow
1️⃣ Data Collection

Dataset: Shakespeare’s Hamlet (public domain)

Text extracted and cleaned for model training.

2️⃣ Data Preprocessing

Tokenization of text corpus.

Conversion to input–output word sequences.

Padding to standardize input length.

Split into training and validation sets.

3️⃣ Model Architecture

Embedding Layer – converts words into vector representations

Two LSTM Layers – captures long-term dependencies in text

Dense + Softmax Output – predicts probability distribution of next word

4️⃣ Model Training

Loss: Categorical Cross-Entropy

Optimizer: Adam

Early Stopping based on validation loss to prevent overfitting.

5️⃣ Evaluation & Testing

Tested with manually constructed prompts.

Qualitative evaluation through predicted completions.

6️⃣ Deployment (Streamlit)

User enters a partial sentence.

Model generates and displays predicted next word.

Real-time interaction with auto-complete type prediction.

