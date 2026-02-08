

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

