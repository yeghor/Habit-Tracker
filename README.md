# Habit Tracker


https://github.com/user-attachments/assets/e68d1d01-4df0-4f20-a24a-acf480ca7bf6


A full-stack habit tracking app with user authentication and XP/level progression.

### Features:
- Secure **JWT-based** authorization (stored in HTTP-only cookies)
- Password hashing with **Bcrypt**
- XP/Level system
- **Habit tracking**:
  - Custom reset periods (daily, weekly, etc.)
  - Marking habits as completed
  - Completion history page
  - Automatic resetting by scheduled task (adjustable via `.env`)
- Optimistic UI for fast interactions
- API-side **rate limiting**
- Error handling (backend/server failures, bad requests)
- Color theme persistence (stored in localStorage)

---

## Stack

### Backend (Python)
- FastAPI
- SQLAlchemy
- Uvicorn
- JWT Auth
- Bcrypt

### Frontend (JavaScript)
- React
- TailwindCSS

---
## Issues
Bad. Like Really terrible request response error handling.

For example: you can get Internal Server Error on API response status code 400 _(bad request)_

Soon will be fixed.

---
## Usage

> Requires: **Python 3.10+**, **Node.js 16+**, **Docker**

Clone the repository:
```bash
git clone https://github.com/yeghor/Fullstack-Habit-Tracker-React-fastAPI.git
```

Move to the applization directory:
```bash
cd Fullstack-Habit-Tracker-React-fastAPI
```

Build and start your docket compose:
```bash
docker compose up
```

#### _Access_
- Frontend: http://0.0.0.0:3000
- Backend: http://0.0.0.0:8000 (fastAPI default)

## **Happy application testing and building your own habits!**
