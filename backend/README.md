

## structure

```
backend/
│
├── app/
│   ├── main.py               
│   ├── database.py           
│
│   ├── models/               
│   │   ├── __init__.py
│   │   ├── user.py           
│   │   ├── patient.py        
│   │   ├── record.py          
│   │   ├── consent.py          
│
│   ├── schemas/               
│   │   ├── __init__.py
│   │   ├── user.py
│   │   ├── patient.py
│   │   ├── record.py
│
│   ├── routers/                
│   │   ├── __init__.py
│   │   ├── auth.py            
│   │   ├── patient.py         
│   │   ├── doctor.py          
│   │   ├── hospital.py        
│   │   ├── admin.py           
│
│   ├── utils/                
│   │   ├── __init__.py
│   │   ├── security.py        
│   │   ├── roles.py           
│   │   └── health_id.py       
│
│   └── config.py               
│
├── requirements.txt
└── README.md
```

# Backend Manual

## Prerequisites
- Python 3.10+ installed
- `pip` available in PATH

## Create and Activate Virtual Environment

### Windows (PowerShell)
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

## Install Dependencies
```bash
pip install -r requirements.txt
```


## Run the API (local dev)
From the `backend/` folder:
```bash
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```
