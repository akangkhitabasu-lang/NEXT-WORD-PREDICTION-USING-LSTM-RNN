# 🔮 Next Word Prediction with LSTM & Early Stopping

Welcome to the **Next Word Prediction** project! 🚀 This application uses a Long Short-Term Memory (LSTM) Recurrent Neural Network (RNN) to predict the next word in a sequence of text. It's built with TensorFlow/Keras and deployed using Streamlit for an interactive web experience. 🌟

## 📜 About the Project

This project demonstrates the power of Deep Learning in Natural Language Processing (NLP). By training on the classic text **Hamlet**, the model learns the patterns and structure of the language to suggest the most probable next word. 🧠✨

## ✨ Features

- **🤖 LSTM Model:** Utilizes a robust LSTM architecture for sequence prediction.
- **🛑 Early Stopping:** Implements early stopping during training to prevent overfitting and ensure optimal performance.
- **🌐 Streamlit Web App:** A user-friendly interface to interact with the model in real-time.
- **⌨️ Interactive Input:** Simply type a sequence of words, and the model predicts what comes next!

## 🛠️ Technologies Used

- **Python** 🐍
- **TensorFlow / Keras** 🧠
- **Streamlit** 👑
- **NumPy** 🧮
- **Pickle** 🥒

## 🚀 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/akangkhitabasu-lang/NEXT-WORD-PREDICTION-USING-LSTM-RNN.git
    cd NEXT-WORD-PREDICTION-USING-LSTM-RNN
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirments.txt
    ```

3.  **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

4.  **Enjoy predicting!** 🎉 Open your browser to the provided local URL and start typing!

## 📂 Project Structure

- `app.py`: The main Streamlit application file. 🖥️
- `next_word_lstm.h5`: The trained LSTM model file. 💾
- `tokenizer.pickle`: The tokenizer object used for preprocessing. 🔡
- `hamlet.txt`: The source text used for training the model. 📖
- `experiments.ipynb`: Jupyter notebook for model training and experiments. 🧪

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request. Let's make this predictor even better! 💪

---
Made with ❤️ by [Your Name]