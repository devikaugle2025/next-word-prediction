Next Word Prediction System using NLP and Deep Learning

📌 Project Overview
This project predicts the next word in a sentence using Deep Learning models (RNN and LSTM). The model is trained on scientist quotes and deployed using Streamlit for real-time text generation.

🚀 Technologies Used
- Python
- NumPy, Pandas, Matplotlib, Seaborn
- TensorFlow & Keras
- NLP (Tokenization, Padding, Embeddings)
- Streamlit (Frontend)

📊 Features
- Text preprocessing (lowercasing, punctuation removal, tokenization)
- Sequence generation and padding
- RNN and LSTM deep learning models
- Next-word and multi-word prediction
- Interactive web interface using Streamlit

🧠 Model Architecture
- Embedding Layer (50 dimensions)
- RNN / LSTM Layer (150 units)
- Dense Softmax Output Layer

📂 Dataset
Scientist Quotes Dataset used for training language model.

▶️ How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
