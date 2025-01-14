# CDP-Chatbot-and-Google-Sheets-Clone
This repository contains two distinct projects as part of the Zeotap assignment

Google Sheets Clone: A web application mimicking Google Sheets with core functionalities like mathematical functions, data quality features, and spreadsheet UI.
CDP Chatbot: A conversational chatbot that answers "how-to" questions related to Customer Data Platforms (CDPs) such as Segment, mParticle, Lytics, and Zeotap.


Table of Contents
1.Project Structure
2.Tech Stack
3.Setup Instructions
4.Backend (Chatbot Server)
5.Frontend (Chatbot)
6.Google Sheets Clone
7.Features
8.Google Sheets Clone
9.CDP Chatbot
10.Future Enhancements


Project Structure------

cdp-chatbot-and-google-sheets-clone/  
├── backend/  
│   ├── server.py  
│   ├── requirements.txt  
│   └── README.md  
├── chatbot-frontend/  
│   ├── public/  
│   ├── src/  
│   ├── package.json  
│   └── README.md  
├── google-sheets-clone/  
│   ├── frontend/  
│   │   ├── public/  
│   │   ├── src/  
│   │   ├── package.json  
│   │   └── README.md  
└── README.md  


Tech Stack
1. Backend (Chatbot Server)
Language: Python
Framework: Flask
Libraries:
langchain: For conversational AI logic.
openai: To integrate GPT-based models.
requests: For making API calls.
2. Frontend
Chatbot
Framework: React.js
Libraries:
Axios: For API calls to the chatbot backend.
Google Sheets Clone
Framework: React.js
Libraries:
react-data-grid: For creating spreadsheet-like UI.
Bootstrap: For styling.


Features

Google Sheets Clone
Spreadsheet Interface: Rows and columns with an interactive grid.
Mathematical Functions:
SUM, AVERAGE, MAX, MIN, COUNT.
Data Quality Functions:
TRIM, UPPER, LOWER, REMOVE_DUPLICATES, FIND_AND_REPLACE.
Data Entry and Validation: Input validation for ensuring data quality.
Bonus Features:
Save/load spreadsheets.
Visualization support with Chart.js.

CDP Chatbot
Dynamic Responses: Retrieves answers from official documentation for Segment, mParticle, Lytics, and Zeotap.
Question Variations: Handles variations in queries and provides relevant information.
Bonus Features:
Cross-CDP comparisons.
Advanced query handling.


Future Enhancements
Google Sheets Clone:

Add advanced formulas and conditional formatting.
Integrate with a backend to save spreadsheet data persistently.
CDP Chatbot:

Enable voice-based query support.
Extend chatbot functionalities to include more CDP platforms.
Deployment:

Deploy both applications to cloud platforms (e.g., AWS, Heroku) for public access.
