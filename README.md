# LapGuard AI

## Laptop Health Maintenance and Advisory System

LapGuard AI is an AI-powered web application designed to monitor laptop health, analyze hardware conditions, predict component Remaining Useful Life (RUL), and provide personalized maintenance recommendations.

The system combines real-time hardware monitoring, machine learning based prediction, rule-based health analysis, and Generative AI to help users understand and maintain their laptop hardware.

## Features

* Real-time laptop hardware monitoring
* CPU usage, temperature, and clock monitoring
* Battery health and charging information
* HDD/SSD health monitoring
* Component Remaining Useful Life prediction
* GRU-based machine learning models
* AI-powered laptop health analysis
* Generative AI advisory chatbot
* Personalized maintenance recommendations
* Health history
* PDF health report generation
* User authentication
* Dark and light mode

## System Architecture

<img width="1052" height="678" alt="image" src="https://github.com/user-attachments/assets/e8f3e0a3-72ac-402b-98c0-9a9c3b60575c" />

```

## Machine Learning

LapGuard AI uses GRU based models for Remaining Useful Life prediction of laptop components.

The system analyzes hardware health indicators and estimates the remaining useful life of components.

### Model Results

| Component | Model |   R² |
| --------- | ----- | ---: |
| CPU       | GRU   | 0.92 |
| Battery   | GRU   | 0.95 |
| Storage   | GRU   | 0.90 |

Additional evaluation metrics include MAE, RMSE, MAPE, precision, and recall.

## Generative AI

The system includes an AI advisory component that analyzes laptop health information and generates recommendations.

The advisory system can provide:

* Health issue category
* Severity
* Possible causes
* Diagnosis summary
* Recommended actions
* Hardware risk
* Repair recommendation

## Technology Stack

### Frontend

* React
* Vite
* JavaScript
* HTML
* CSS

### Backend

* Python
* Flask
* REST APIs

### Machine Learning

* Python
* GRU
* LSTM
* Regression
* Scikit-learn

### Hardware Monitoring

* psutil
* WMI
* PowerShell

### Generative AI

* Large Language Models
* OpenRouter API

### Database

* SQLite
* Supabase

## Project Structure

```text
lapguard-ai/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── app.py
│   ├── models/
│   └── requirements.txt
│
├── auth-backend/
│   ├── server.js
│   └── package.json
│
├── .gitignore
├── .env.example
└── README.md
```

## Installation

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Python Backend

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask backend:

```bash
python app.py
```

### Authentication Backend

```bash
cd auth-backend
npm install
npm start
```

## Environment Variables

Create a `.env` file for your local environment.

Do not upload API keys or passwords to GitHub.

Use `.env.example` as a template:

```text
OPENROUTER_API_KEY=your_api_key_here
```

## Screenshots
<img width="1915" height="873" alt="image" src="https://github.com/user-attachments/assets/6f360a4e-099b-4ba2-8707-6aa30fd82749" />
<img width="1917" height="890" alt="image" src="https://github.com/user-attachments/assets/89ed4678-acfe-4172-9c92-ca751e443c5c" />
<img width="1911" height="875" alt="image" src="https://github.com/user-attachments/assets/56ac8168-5110-41d2-bc8c-d9d724fef0f5" />
<img width="1915" height="858" alt="image" src="https://github.com/user-attachments/assets/544226d3-bc65-4393-b3bb-9a78ddafaac4" />
<img width="1916" height="873" alt="image" src="https://github.com/user-attachments/assets/9cc68140-6eac-4e3b-a66c-02a1a6fdcd46" />



## Project Goals

The main goals of LapGuard AI are to:

1. Monitor laptop hardware health in real time.
2. Identify potential hardware problems.
3. Predict component remaining useful life.
4. Provide understandable AI-based maintenance advice.
5. Help users reduce unexpected hardware failures and maintenance costs.

## Future Improvements

* Improved RUL prediction using larger real-world datasets
* Additional hardware health indicators
* More advanced anomaly detection
* Expanded multilingual support
* Improved personalization of maintenance recommendations

## Author

**Amna Iqbal**

Computer Science Graduate
AI / Machine Learning / Generative AI

GitHub: [@amna02](https://github.com/amna02)
