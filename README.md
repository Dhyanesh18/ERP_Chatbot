# ERP System Explanation Chatbot

This chatbot is designed to explain the key functionalities of an ERP (Enterprise Resource Planning) system. It provides detailed information about various features such as document extraction, name entity recognition, document classification, and more.

## Setup

1. Ensure you have Python 3.9.18 installed.
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
   Before training the model, make sure that python 3.9.18 is selected as the interpreter in vscode
   ```
3. Train the model:
   ```
   rasa train
   ```
4. To run the chatbot, use:
   ```
   rasa shell
   ```

## Features

The chatbot can explain the following ERP functionalities:
- Document Extraction
- Name Entity Recognition
- Document Classification
- Document Digitalization
- Search Functionality
- User Verification
- Business Rules Application
- Accounts Management
- Financial Features
- Payment Reminders

## Customization

To add new features or modify existing ones:
1. Update the intents and examples in `data/nlu.yml`
2. Add or modify conversation flows in `data/stories.yml`
3. Update the domain configuration in `domain.yml`
4. If needed, add custom actions in `actions.py`

After making changes, retrain the model using `rasa train`.

## Note

This chatbot is a demonstration model and does not connect to an actual ERP system yet. It's designed to provide an command-line interface to interact with the chatbot.
It can be connected to a real ERP system using Flask API.

### Team members and contributions

1. DHYANESHVAR K - Most of the code part, logic, setting up, version control & inputs for the PPT.
2. ADITHYA RAM S - Adding examples for intents.
3. SHARATH C - Adding and managing stories.
4. HARI VIGNESH M - PPT.