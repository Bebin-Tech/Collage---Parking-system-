# Parkwise College Parking

A React dashboard and Django/SQLite API prototype for smart college parking operations.

## Run the backend

```powershell
cd backend
py manage.py migrate
py manage.py runserver
```

API endpoints:

- `GET /api/dashboard/`
- `PATCH /api/slots/A-01/` with `{"status":"occupied"}`

## Run the frontend

In another terminal:

```powershell
cd frontend
npm run dev
```

Open the Vite URL shown in the terminal. The dashboard includes live slot toggles, slot search, activity, vehicle navigation, and an occupancy forecast view. The UI is seeded for demonstration and is ready to connect to the Django API.
