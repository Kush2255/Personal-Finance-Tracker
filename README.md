📊 Personal Finance Tracker

👨‍💻 Author: Kushwanth Rasala

📌 Project Overview

The Personal Finance Tracker is a Python desktop application that allows users to manage their daily income and expenses with ease. It provides authentication, categorization, filtering, and data visualization features, along with options to export reports. This makes it a simple yet powerful tool for personal financial management.

🚀 Features

🔑 User Authentication (Login & Register)

💵 Add Transactions (Income/Expense with category & date)

📅 Filter Transactions by category and date range

📊 Data Visualization with Matplotlib & Seaborn (Bar & Pie Charts)

📑 Export Reports to CSV/Excel

🗄 SQLite Database for secure local storage

📦 Packaged as Desktop App (via PyInstaller)

🏗 Tech Stack

Language: Python

Libraries: tkinter, pandas, matplotlib, seaborn, plotly, tkcalendar, openpyxl, reportlab

Database: SQLite3

IDE: VS Code

📂 Project Structure
personal_finance_tracker/
│── main.py           # Main Tkinter GUI App
│── db.py             # Database operations
│── auth.py           # Authentication system
│── visualization.py  # Data visualization (charts)
│── export.py         # Export functions (CSV/Excel)
│── requirements.txt  # Dependencies
│── data/             # SQLite DB + Exported reports

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/Kush2255/Personal-Finance-Tracker.git
cd Personal-Finance-Tracker


2️⃣ Create Virtual Environment (recommended)

python -m venv venv


Activate it:

Windows → venv\Scripts\activate

macOS/Linux → source venv/bin/activate

3️⃣ Install Dependencies

pip install -r requirements.txt


4️⃣ Run the Application

python main.py

📦 Packaging as Executable

To create a standalone app:

pip install pyinstaller
pyinstaller --onefile main.py


The executable will be available inside the dist/ folder.

🌟 Future Enhancements

📑 Export to PDF with styled reports

🎨 Improve Tkinter UI (themes, icons, responsiveness)

📊 Add more interactive charts with Plotly

🔒 Encrypt user passwords for stronger security

✨ Author

👨 Kushwanth Rasala
