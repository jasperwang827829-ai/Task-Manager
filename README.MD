# Task Management Web Application

A full-stack task management web application built with React, FastAPI, and SQLite.

## Features

- Create tasks
- View task list
- Update task completion status
- Delete tasks
- Filter tasks by status

## Tech Stack

### Frontend
- React
- Vite
- Axios

### Backend
- FastAPI
- SQLAlchemy

### Database
- SQLite

## Project Structure

task-manager/
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── database.py
│   │   ├── models.py
│   │   ├── schemas.py
│   │   └── crud.py
│   └── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── api.js
│   │   ├── main.jsx
│   │   └── index.css
└── README.md

## How to Run

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload