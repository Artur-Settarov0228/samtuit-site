```
davomat/
├── config/                     # project settings
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── asgi.py
│
├── apps/
│   ├── users/                 # auth + teacher
│   ├── students/              # student + parent
│   ├── attendance/            # NB logic
│   ├── notifications/         # bot integration
│   └── schedules/             # jadval (optional)
│
├── templates/                 # Django template frontend
│   ├── base/
│   ├── dashboard/
│   ├── attendance/
│   └── auth/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── manage.py
└── requirements.txt
```