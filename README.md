# Sentiment Analysis App

This is a Sentiment Analysis web application built using Python, Gradio, and the Hugging Face `transformers` library.

## Features
- Analyzes the sentiment of input text (Positive/Negative).
- Supports multi-line input to analyze several sentences at once.
- Displays both the sentiment label and a confidence score percentage.

## Local Setup
1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Deployment
This repository is pre-configured for deployment on platforms like Render. Ensure `runtime.txt` and `requirements.txt` are included in the root directory.
