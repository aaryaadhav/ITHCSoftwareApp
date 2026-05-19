# Deployment Instructions

## Prerequisites
- Python installed
- Node.js installed
- Jenkins configured

## Steps

1. Clone repository:
   git clone https://github.com/aaryaadhav/ITHCSoftwareApp.git

2. Setup backend:
   cd backend
   python -m venv venv
   pip install -r requirements.txt

3. Setup frontend:
   cd frontend
   npm install
   npm start

## CI/CD Deployment
- Jenkins pipeline handles build and deployment automatically

## Rollback
- Revert to previous release version if needed
