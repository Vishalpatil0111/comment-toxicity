# 🗣️ Comment Toxicity Model

Welcome to the Comment Toxicity Model project! This repository contains a machine learning model that uses a sequential model with LSTM layers to detect various forms of toxicity in text comments. The model is trained on a dataset with the following columns: `comment_text`, `toxic`, `severe_toxic`, `obscene`, `threat`, `insult`, and `identity_hate`. Additionally, we have integrated this model with Gradio for an interactive web interface.

## 🌟 Features

- **Sequential Model**: Utilizes a sequential model architecture for simplicity and effectiveness.
- **LSTM Layers**: Long Short-Term Memory (LSTM) layers to capture temporal dependencies in text.
- **Toxicity Detection**: Detects multiple forms of toxicity including:
  - 🧨 Toxic
  - 🚨 Severe Toxic
  - 🗯️ Obscene
  - ⚠️ Threat
  - 🤬 Insult
  - 🆔 Identity Hate
- **Interactive Interface**: Integrated with Gradio to provide an easy-to-use web interface.

## 📊 Dataset

The model is trained on a dataset with the following columns:
- `comment_text`: The text of the comment.
- `toxic`: Binary label indicating if the comment is toxic.
- `severe_toxic`: Binary label indicating if the comment is severely toxic.
- `obscene`: Binary label indicating if the comment is obscene.
- `threat`: Binary label indicating if the comment contains threats.
- `insult`: Binary label indicating if the comment contains insults.
- `identity_hate`: Binary label indicating if the comment contains identity hate speech.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/comment-toxicity-model.git
   cd comment-toxicity-model
