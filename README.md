## ✨ **Flask Paraphrasing App**

A Flask-based web application that utilizes a Pegasus model for text paraphrasing. The app allows users to input text and generate multiple paraphrased versions using beam search.

## 📖 **Overview**

This project demonstrates:

A Flask web interface for paraphrasing text.

Usage of a pretrained Pegasus model for conditional text generation.

A simple and interactive way to get multiple paraphrased outputs.

## 📂 **Features**

✨ Text Paraphrasing: Generates multiple rewritten versions of input text.

🔍 Beam Search Optimization: Uses a configurable beam search mechanism.

🖥️ Web Interface: Built using Flask for easy access via a browser.

📦 Pretrained Model Support: Uses Hugging Face's transformers library.

## 🛠️ **Methodology**

 🚀 **Model Loading**

Loads a pretrained Pegasus model from the model/ directory.

Loads a tokenizer from the tokenizer/ directory.

## 🔧 **Text Processing**

Converts input text into tokenized format.

Uses beam search and temperature scaling to generate multiple outputs.

Decodes generated outputs into human-readable sentences.

## 🌐 **Web Interface**

Home Route (/): Displays the main page.

Paraphrasing Route (/paraphrase): Accepts user input and returns paraphrased text.

## 📊 **Example Usage**

Open the web interface.

Enter a sentence you want to paraphrase.

Select the number of paraphrased outputs.

Click submit to see variations of the input sentence.

## **Example Input:**

Text: "Artificial Intelligence is transforming the world."
Number of Paraphrases: 3

## **Example Output:**

1. AI is changing the world.
2. The world is being transformed by artificial intelligence.
3. Advances in AI are reshaping the globe.

## 🚀 **Installation & Usage**

📦 Requirements

Python 3.x

Flask

Transformers (Hugging Face)

## 🔧 **Setup**

pip install flask transformers

## ▶️ **Running the Application**

Ensure the model/ and tokenizer/ directories exist.

Run:

python app.py

Open your browser and go to http://127.0.0.1:5000/.

## 📌 **Future Improvements**

🧠 More Models: Support for additional NLP models like GPT.

🌐 API Endpoint: Expose paraphrasing as a REST API.

🎨 UI Enhancements: Improve the frontend design.

🔠 Multilingual Support: Allow paraphrasing in different languages.

## 🚀 Stay tuned for updates!

