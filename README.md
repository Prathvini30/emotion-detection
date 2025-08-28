Emotion Detection
Overview

The Emotion Detection project is a machine learning application designed to analyze and classify human emotions from facial expressions using deep learning techniques. This project leverages a pre-trained model to identify emotions such as happiness, sadness, anger, surprise, fear, disgust, and neutral states.

Features

Emotion Classification: Detects and classifies facial expressions into seven distinct emotions.

Real-Time Analysis: Capable of processing live video streams for immediate emotion recognition.

User-Friendly Interface: Built with Streamlit for an intuitive and interactive user experience.

Pre-trained Model: Utilizes a MobileNetV2 model fine-tuned on a facial emotion dataset for accurate predictions.

Technologies Used

Python: Programming language for backend development.

Streamlit: Framework for building the interactive web interface.

TensorFlow/Keras: Deep learning libraries for model implementation.

OpenCV: Library for video capture and image processing.

Hugging Face Transformers: For advanced NLP tasks (if applicable).

Installation & Setup
1. Clone the Repository
git clone https://github.com/Prathvini30/emotion-detection.git
cd emotion-detection

2. Set Up Virtual Environment
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Run the Application
streamlit run frontend/app.py

Usage

Launch the application using the command above.

Grant camera access when prompted.

The application will display a live feed and analyze facial expressions in real-time.

Detected emotions will be shown with corresponding confidence scores.

Future Enhancements

Multi-Modal Emotion Detection: Incorporate voice and text analysis for a comprehensive emotion recognition system.

Model Optimization: Improve model accuracy and performance for better real-time analysis.

User Authentication: Add user login and profile features for personalized experiences.
