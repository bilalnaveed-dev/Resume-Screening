# 🧠 AI Resume Screening System

An AI-powered tool to automate the resume screening process using Natural Language Processing (NLP) and machine learning techniques. This project was developed as part of my 4th semester AI coursework and aims to streamline recruitment by intelligently ranking candidates based on job descriptions.

## 🚀 Features

- 📄 **Resume Parsing**: Supports PDF, DOCX, and TXT formats
- 🔍 **AI-Powered Ranking**: Uses TF-IDF, heuristic A* search, and naive keyword scoring
- 📊 **Interactive Dashboard**: Displays ranked candidates with match scores and key highlights
- 🔒 **Secure & Scalable**: Designed for local or containerized deployment

## ⚙️ Technology Stack

- **Backend**: Python, Flask  
- **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript  
- **NLP & ML**: spaCy, scikit-learn  
- **Data Processing**: pandas, NumPy  
- **Deployment**: Localhost or Docker

## 📈 Project Objectives

- Automate initial resume screening to reduce manual effort
- Improve the accuracy of candidate-job matching
- Minimize human bias in recruitment decisions
- Provide a scalable, extensible solution for real-world use

## 📂 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/resume-screening-system.git
   cd resume-screening-system

2. **Create Virtual Environment**
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install Dependencies**
pip install -r requirements.txt

4. **Run the Flask server**
python app.py

5. **Open the app in your browser at:**
http://127.0.0.1:5000/

