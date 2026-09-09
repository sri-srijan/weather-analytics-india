# Weather Analytics India

A historical weather analytics web application for Indian states and cities.

## Current status

This repository starts from the existing Delhi Weather Report HTML prototype.

### Current frontend
- Existing report design preserved
- Existing summary cards preserved
- Existing monthly temperature table preserved
- Existing extreme-weather section preserved
- CSS separated into `frontend/css/style.css`
- JavaScript entry point created at `frontend/js/app.js`

### Planned architecture

Frontend:
- HTML/CSS/JavaScript prototype
- Later migration to React

Backend:
- Python + FastAPI
- Open-Meteo historical weather API
- Pandas/NumPy for analysis

Database:
- SQLite initially
- PostgreSQL later if needed

## Folder structure

```text
weather-analytics-india/
├── frontend/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
├── backend/
│   └── README.md
├── data/
│   └── locations.json
├── notebooks/
└── README.md
```

## First milestone

Make the existing report dynamic:
State → Capital → Year range → Generate Report.
