Tamil Audio to AI Processing Pipeline

Overview

This project provides a Gradio-based interface for processing Tamil audio files. It performs the following steps:

Transcribes Tamil audio into Tamil text using the Groq API.

Translates the Tamil text to English.

Generates an image based on the translated English text using a Hugging Face model.

Generates further text from the translated English text using the Groq API.

Features

Tamil speech-to-text conversion (using Whisper)

Tamil-to-English translation

AI-generated images from text prompts

AI-generated text from an initial prompt

User-friendly interface powered by Gradio

Prerequisites

Before running the script, ensure you have the following:

Python installed (>=3.7)

Required Python packages:

pip install gradio requests pillow groq

A valid Groq API Key

A Hugging Face model endpoint for image generation

Installation

Clone this repository:

git clone https://github.com/REBINFERNART/tamil-audio-ai.git
cd tamil-audio-ai

Install dependencies:

pip install -r requirements.txt

Set up environment variables for API keys (or update them in the script):

export GROQ_API_KEY="your_groq_api_key"

Usage

Run the following command to launch the Gradio interface:

python app.py

Then, upload a Tamil audio file, and the pipeline will process it and display the results.

File Structure

.
├── deploy.py                 
├── requirements.txt       
├── README.md              

API References

Groq API

Hugging Face Inference API

License

This project is licensed under the MIT License.

Author

[K.REBIN FERNART] - [krebinfernart@gmail.com]
