🔥 BurnoutIQ – Smart Productivity & Burnout Analysis System

📌 Overview

**BurnoutIQ** is a web-based application designed to analyze student productivity and detect burnout risk based on daily habits.
It helps users understand how factors like study time, focus, sleep, and task completion affect their performance and well-being.

🚀 Features

* 📊 Productivity score calculation
* ⚠️ Burnout risk classification (Low, Medium, High)
* 🧠 Multi-factor analysis (study, focus, sleep, tasks)
* 🌐 Simple web interface using Flask
* 📈 Easy to extend with graphs and AI models

🛠️ Tech Stack
Backend: Python (Flask)
Frontend: HTML (Jinja2 Templates)
Libraries: NumPy

📂 Project Structure

BurnoutIQ/
│
├── app.py
├── requirements.txt
└── templates/
    └── index.html

⚙️ Installation & Setup
1️⃣ Clone the repository

git clone https://github.com/your-username/BurnoutIQ.git
cd BurnoutIQ

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the application
python app.py

🌐 Usage

1. Open your browser
2. Go to:

http://127.0.0.1:5000/

3. Enter:

   * Study Hours
   * Focus Level
   * Sleep Hours
   * Task Completion

4. Click **Analyze** to view:

   * Productivity Score
   * Burnout Risk Level

How It Works

The system calculates productivity using a weighted formula:

* Study Hours → 30%
* Focus Level → 30%
* Sleep → 20%
* Task Completion → 20%

Based on the score:

Low Risk:High productivity
Medium Risk:Moderate productivity
High Risk:Low productivity

🔮 Future Enhancements

* 📉 Graphs & data visualization
* 🤖 AI-based burnout prediction
* 📱 Mobile application
* 🔔 Smart recommendations
