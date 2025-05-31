# GPT-2 Text Generator App

This is a simple text generation web app using OpenAI's GPT-2 model and Gradio.

## 🔍 Description
The app takes a text prompt as input and generates a continuation using a pre-trained GPT-2 model with beam search decoding.

## 📁 Files Included
- `app.py` — Main application code using Gradio and Transformers
- `requirements.txt` — List of required Python packages
- `README.md` — Project overview and instructions

## 🚀 How to Run

### 1. Clone the Repository

git clone https://github.com/your-username/gpt2-text-generator.git
cd gpt2-text-generator

### 2. Install Dependencies

pip install -r requirements.txt

### 3. Run the App

python app.py

The app will launch in your browser using Gradio!

## 📦 Requirements

* Python 3.7+
* gradio
* tensorflow
* transformers

## 🧠 Model

Uses the `gpt2` model from Hugging Face 🤗 Transformers.

### ✨ Example

Input: Once upon a time

Output: Once upon a time there was a curious little dragon who loved to explore the forest...
