This is a Flask-based web application, designed to simulate a voting platform for Polytechnic University of the Philippines Biñan.

The system uses:
- Flask-SQLAlchemy for database management
- Flask-Login for user authentication
- Flask-SocketIO for live updates

## Features
**For Students**
- Scroll through posts by admins and candidates
- Vote once the voting is open (one vote per user)
- View live voting results updated in real time

**For Candidates**
- Post campaign
  
**For Admins**
- Post announcements or updates
- Manage the list of candidates and control whether voting is open or closed

## Prerequisites

- Python 3.10+ (tested with Python 3.13)
- DB Browser for SQLite

## Setup Instructions

1. **Open terminal and go to project directory**
2. **Create a virtual environment**
```bash
py -m venv venv
```
3. **Activate the virtual environment**
```bash
.\venv\Scripts\Activate.ps1
```
Your terminal prompt should now start with (venv).
4. **Install the dependencies**
```bash
pip install -r requirements.txt
```
5. **Run the application**
```bash
py main.py
```
6. **Open in browser**
Visit http://127.0.0.1:5000 to use the app.

## Database
A *pre-populated SQLite database* is included for demonstration purposes, so the system can be run immediately after setup.

Open the database in DB Browser to select a user login credential.
