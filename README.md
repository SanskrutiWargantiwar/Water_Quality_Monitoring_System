# Water Quality Monitoring System

## Overview

The Water Quality Monitoring System is a full-stack web application
designed to monitor water stations and provide users with access to
water-quality information.

## Features

- User registration and authentication
- JWT-based authentication
- Water station management
- Water station information
- PostgreSQL database
- REST APIs
- React-based frontend
- FastAPI backend

## Technology Stack

### Frontend
- React.js
- Tailwind CSS
- JavaScript


### Backend
- Python
- FastAPI
- SQLAlchemy
- PostgreSQL

### Authentication
- JWT
- Password hashing

## Project Structure

water-quality-monitor/
├── backend/
├── frontend/
├── README.md
└── .gitignore

## Local Setup

### Backend

cd backend

python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload

### Frontend

cd frontend

npm install

npm run dev
