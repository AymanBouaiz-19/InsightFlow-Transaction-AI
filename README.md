# 💼 InsightFlow – Transaction AI

🔎 A next-generation financial data analyzer powered by Python & AI.  
InsightFlow helps users understand, predict, and optimize their transaction flow using automated anomaly detection, smart categorization, and machine learning-driven forecasting.

> ⚠️ This project is under development. UI & cloud features are coming soon.

---

## 🚀 Why InsightFlow?

Managing transactions isn’t just about looking at numbers — it’s about finding **patterns**, spotting **anomalies**, and making **intelligent decisions**.  
InsightFlow empowers developers, analysts, and even individuals to take control of financial data using AI-powered tools, all built from scratch by an AI engineering student.

---

## 🧠 Key Features

| Feature                   | Description                                                                         |
|---------------------------|-------------------------------------------------------------------------------------|
| 🧹 Clean & Normalize       | Load messy bank CSV/Excel files and prepare them for analysis                      |
| 🧠 Anomaly Detection       | Detect unusual transactions via Isolation Forest / Z-Score                         |
| 📊 Expense Forecasting     | Predict future expenses using ML models like Prophet or Linear Regression         |
| 🧩 Smart Categorization     | Automatically assign categories to transactions using rules or ML (coming soon)   |
| 📄 Report Generation       | Export clean summaries and insights to PDF, CSV, or dashboard format              |
| 📬 Notifications (Planned) | Email alerts for unusual patterns or budget breaches                              |
| 🌐 Dashboard UI (Planned)  | Streamlit or Flask-based interactive web app                                      |
| 🌍 Multilingual Support    | Arabic, French, and English (interface planned with RTL support)                  |

---

## 🧱 Tech Stack

| Component       | Technologies                      |
|----------------|-----------------------------------|
| Language        | Python                            |
| Data Handling   | Pandas, NumPy                      |
| ML / AI         | Scikit-learn, Prophet (Meta), Isolation Forest |
| Visualization   | Matplotlib, Seaborn                |
| Reporting       | PDFKit, FPDF, Jinja2               |
| Optional UI     | Streamlit or Flask (in development)|
| Deployment      | GitHub + Docker + Streamlit Cloud (planned) |

---

## 🧩 Project Structure

InsightFlow/ ├── data/                  # Sample datasets or user-uploaded files ├── models/                # Trained or serialized ML models ├── reports/               # Generated reports (PDF/CSV) ├── src/ │   ├── main.py            # Entry point │   ├── cleaner.py         # Data cleaning functions │   ├── detector.py        # Anomaly detection logic │   ├── forecaster.py      # ML-based expense prediction │   ├── categorizer.py     # Rule-based or AI categorization │   └── reporter.py        # PDF/CSV report generation ├── dashboard/             # (Planned) UI components ├── requirements.txt └── README.md

---

## 🧪 Example Usage

```python
from src.main import InsightFlow

analyzer = InsightFlow("data/july_transactions.csv")
analyzer.clean()
analyzer.categorize()
analyzer.detect_anomalies()
analyzer.forecast()
analyzer.generate_report("reports/july_summary.pdf")


---

📊 Sample Output (Planned)

🧾 PDF Summary: Daily/weekly spending breakdown

📈 Charts: Forecasted vs actual expenses

🛑 Anomaly Table: Highlighted strange transactions

💼 Category Pie Chart: Food, Transport, Bills, etc.



---

🌐 Roadmap

[x] Transaction cleaning engine

[x] Anomaly detection module

[x] Forecast model integration

[ ] Smart ML categorization (next step)

[ ] Interactive Streamlit UI

[ ] Email alert system

[ ] OAuth login + multi-user support



---

👨‍💻 Author

Ayman Bouaziz
AI & Software Engineering Student – Faculty of Science and Technology Al Hoceima
📍 Morocco | 🧠 Python • Data Science • AI • Web
🔗 LinkedIn :  https://www.linkedin.com/in/ayman-bouaziz-7ab181349


✉️ projects.aymanbouaziz@gmail.com


---

📜 License

MIT License — For research, educational and personal use.
© 2025 Ayman Bouaziz


---

🧠 Final Thought

> InsightFlow is not just a tool — it's your personal AI financial advisor, built line by line with passion and precision.