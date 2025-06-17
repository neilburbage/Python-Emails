# Python Emails

### Send emails from your favourite IDE.
**This is a lightweight Gmail SMTP helper with one external dependency.**

---

### Quick start 
**Clone this repo:**  
```git clone git@github.com:neilburbage/Python-Emails```  
```$ cd Python-Emails```  
**Create a virtual environment:**     
```python -m venv .venv```  
```# Linux / macOS: source .venv/bin/activate```     
```# Windows (PowerShell): .venv\Scripts\Activate.ps1```  
```# Windows (cmd): .venv\Scripts\activate.bat```  
**Install dependencies:**    
```pip install -r requirements.txt```  
**Create a gmail test account, and a .env file:**  
```1. Sign up for a new Gmail account, enable 2-factor authentication,```       
```then generate an App Password.```    
```text
EMAIL_ADDRESS=your_test_account@gmail.com
EMAIL_PASSWORD=16-char_app_password
```
**Run the script:**  
```python email_setup.py --to you@example.com --subject "Hello" --body "Test"```

---

### Project layout 
```
├── email_setup.py     # send_email helper
├── requirements.txt   # python-dotenv pinned
├── .env               # Gmail credentials in .gitignore
├── .gitignore         # .venv/, __pycache__/
└── README.md          # you are here
```
---



