# ArtworkBookingChatbot-Sinhala

This repository contain source code for Sinhala artwork booking chatbot created using RASA.

## Directory Structure

The important files and directories of the repository

    ├── data :                  
        ├── nlu.yml : training data for intent classification and entity extraction
        ├── rules.yml : rules for rasa core model training
        ├── stories.yml : sample stories for rasa core training
    ├── models :
        ├── Trained models (in .tar.gz format) 
    ├── actions :
        ├── action.py : custom actions
    ├── results :
        ├── results of model evaluations (confusion matrices, histograms, etc)
    ├── domain.yml : training data for action prediction
    ├── config.yml : model configurations
    ├── endpoints.yml : action server endpoint
    ├── credentials.yml

## Getting started

```commandline
pip install rasa

python3 -m venv ./venv

.\venv\Scripts\activate

git clone https://github.com/AnuttharadeSilva/ArtworkBookingChatbot-Sinhala
 
cd ArtworkBookingChatbot-Sinhala

rasa run --enable-api -cors "*"

```commandline
python -m http.server

Navigate to http://localhost:8000/




