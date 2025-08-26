<<<<<<< HEAD
📊 Personal Finance Tracker with Data Visualization

👩‍💻 Author: Ritwika Saha

📌 Project Overview

The Personal Finance Tracker is a Python desktop application that helps users manage their daily income and expenses, categorize them, and visualize monthly summaries through interactive charts. It provides authentication, filtering, and data export features, making it a simple yet powerful financial management tool.

🚀 Features

🔑 User Authentication (Login & Register)

💵 Add Transactions (Income/Expense with Category & Date)

📅 Filter Transactions by category and date range

📊 Data Visualization with Matplotlib & Seaborn (Bar & Pie Charts)

📑 Export Reports to CSV/Excel

🗄 SQLite Database for local storage

📦 Packaged as Desktop App (via PyInstaller)

🏗 Tech Stack

Language: Python

Libraries: tkinter, pandas, matplotlib, seaborn, plotly, tkcalendar, openpyxl, reportlab

Database: SQLite3

IDE: VS Code

📂 Project Structure
personal_finance_tracker/
│── main.py              # Main Tkinter GUI App
│── db.py                # Database operations
│── auth.py              # Authentication system
│── visualization.py     # Data visualization (charts)
│── export.py            # Export functions (CSV/Excel)
│── requirements.txt     # Dependencies
│── data/                # SQLite DB + Exported reports

⚙️ Installation & Setup

1️⃣ Clone or Download this repository.

git clone https://github.com/ritwikasaha/personal-finance-tracker.git
cd personal-finance-tracker


2️⃣ Create Virtual Environment (recommended)

python -m venv venv


Activate it:

Windows → venv\Scripts\activate

macOS/Linux → source venv/bin/activate

3️⃣ Install Dependencies

pip install -r requirements.txt


4️⃣ Run the Application

python main.py

📸 Screenshots

🔐 Login Screen
💵 Transaction Entry Form
📊 Visualization Dashboard
📑 Exported Excel/CSV Reports

📦 Packaging as Executable

To create a standalone app:

pip install pyinstaller
pyinstaller --onefile main.py


The executable will be available inside the dist/ folder.

🌟 Future Enhancements

📑 Export to PDF with styled reports

🎨 Improve Tkinter UI (Themes, Icons)

📊 Add more interactive charts with Plotly

🔒 Encrypt user passwords for better security

✨ Author

👩 Ritwika Saha
=======
# Personal-Finance-Tracker
>>>>>>> 17cf7dd7810f4a21c2f4ffc013675eeb771ffb3a
