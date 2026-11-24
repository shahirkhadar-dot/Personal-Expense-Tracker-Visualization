# Personal Expense Tracker with Data Visualization

## IMPORTANT: How to run this project

1. Extract this ZIP.
2. Open the folder `Personal-Expense-Tracker-Visualization` in VS Code.
3. Make sure `app.py`, `main.py`, and `requirements.txt` are directly inside the folder you opened.
4. Open **Terminal -> New Terminal** in VS Code.
5. Copy and run these commands ONE AT A TIME:

```powershell
python --version
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

If PowerShell says scripts are disabled, run this first:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then activate again:

```powershell
.venv\Scripts\Activate.ps1
```

When Streamlit starts, the browser should open to:
`http://localhost:8501`

## What to click

When the dashboard opens:
1. Click **Generate Sample Data** in the left sidebar.
2. Look at the charts and tables.
3. Add your own expense using **Add Expense**.
4. Click **Export Reports** to create CSV/Excel reports.

## Stop the dashboard

Return to the terminal and press `Ctrl + C`.

## Project features

- Expense and income entry
- SQLite database
- CSV import
- Category spending analysis
- Monthly spending trend
- Payment method analysis
- Daily spending trend
- Budget check
- CSV and Excel report export
- Streamlit dashboard

## CSV columns

For your own CSV, use:

`date,category,amount,payment_method,description`
<img width="1886" height="957" alt="pic 51" src="https://github.com/user-attachments/assets/d76875ff-8c14-4cfe-b54c-d8448280574e" />
<img width="1882" height="841" alt="pic 52" src="https://github.com/user-attachments/assets/16babc2d-1818-4c90-927f-f2288fb7f855" />
<img width="1851" height="832" alt="pic 53" src="https://github.com/user-attachments/assets/08ff86a8-46e0-4dc3-9749-97f741e8b4c9" />
<img width="1377" height="517" alt="pic 54" src="https://github.com/user-attachments/assets/5b8221f5-00bb-4adb-b977-758720d46f04" />



