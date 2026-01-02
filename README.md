# Mental Health Chatbot

## Project Overview
The **Mental Health Chatbot** is an AI-driven conversational assistant designed to provide mental health support. It engages users in meaningful conversations, offering guidance and resources based on predefined intents.

## Features
- Provides empathetic responses to mental health-related queries.
- Uses NLP techniques to understand and process user inputs.
- Trained on a dataset of mental health-related conversations.
- Built using **Python, TensorFlow/Keras, Flask, and NLP libraries**.

## Installation and Setup

### Prerequisites
Ensure you have **Python 3.7+** installed on your system.

### Steps to Run the Project
1. **Clone or Extract the Project**
   ```bash
   git clone <repository_url>
   cd Mental-health-Chatbot
   ```
   If using the provided ZIP file, extract it and navigate into the project folder.
   

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Chatbot Application**
   ```bash
   python app.py
   ```
   This will start a Flask server, and you can interact with the chatbot via the provided endpoint.

5. **Interacting with the Chatbot**
   Open your browser and navigate to `http://127.0.0.1:5000/` (or any specified port) to begin using the chatbot.

## File Structure
- `app.py` - Main application script for running the chatbot server.
- `intents.json` - Contains chatbot responses and intent categorization.
- `model.h5` - Pre-trained deep learning model for intent classification.
- `training.py` - Script used to train the chatbot model.
- `requirements.txt` - List of dependencies required for running the chatbot.
- `texts.pkl` and `labels.pkl` - Serialized tokenizer and label encoder for text processing.

## Future Improvements
- Enhance the NLP model for better contextual understanding.
- Deploy as a web application with an interactive UI.
- Integrate with mental health resources and support groups.
