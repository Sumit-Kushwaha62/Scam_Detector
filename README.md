## Scam Detector (Flask + Google Generative AI)

### An intelligent Scam Detection Web App built with Flask, Machine Learning, and Google Generative AI.
This project allows users to upload PDF/TXT files or enter a URL and get real-time classification on whether the content/URL is legitimate or fraudulent.

## Features

- Email/Text Scam Detection – Upload a .pdf or .txt file and detect phishing or scam messages.

- URL Classification – Identify if a URL is benign, phishing, malware, or defacement.

- Powered by Google Generative AI (Gemini models) for accurate classification.

- Supports PDF/Text extraction using PyPDF2.

- Secure API key management with .env file.

- Ready for deployment with Gunicorn.

- Tech Stack

## Backend: Flask, Python

- ML/AI: Google Generative AI (Gemini 1.5)

- File Parsing: PyPDF2

- Deployment: Gunicorn, Render

## Project Structure

```

Scam_Detector/
│── main.py          # Flask app entry point
│── requirements.txt # Dependencies
│── templates/
│    └── index.html  # Frontend UI
│── static/          # CSS/JS (if any)
│── .env             # Environment variables

```


## Installation

### Clone the repository

```
git clone https://github.com/Sumit-Kushwaha62/Scam_Detector.git
cd Scam_Detector

```
### Create a virtual environment

```
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```
### Install dependencies
```
pip install -r requirements.txt

```

### Set up environment variables
#### Create a .env file in the project root and add your Google API key:

```
GOOGLE_API_KEY=your_google_api_key_here
```

### Run the Flask app locally:

```
python main.py
```

- Upload a File (PDF/TXT)

- Go to the home page

- Upload a .pdf or .txt file

- Get scam detection results instantly

- URL Classification

- Enter a URL

- Get a classification: benign, phishing, malware, or defacement









[Live Demo](https://scam-detector-010.onrender.com)  

### Screenshot
![Screenshot](https://github.com/Sumit-Kushwaha62/Scam_Detector/blob/main/assets/Screenshot1.png?raw=true)  
![Screenshot](https://github.com/Sumit-Kushwaha62/Scam_Detector/blob/main/assets/Screenshot2.png?raw=true)  
[Contact](https://www.linkedin.com/in/sumit-kushwaha-83b608357/)
