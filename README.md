## Mentally Swasth

Mentally Swasth is a full-stack mental wellness platform built with Flask, designed to help users monitor emotional well-being, engage in peer interaction, and maintain reflective mental health records.

The system integrates secure authentication, real-time communication, and data-driven insights within a responsive web interface.
## Core Features

* Secure Authentication
  Password-less login using email-based One-Time Password (OTP) verification.

* Mood Tracking & Journaling
  Structured logging of emotional states with optional notes and historical access.

* Real-Time Community Chat
  WebSocket-based communication enabling live user interaction.

* Data Visualization
  Interactive charts for analyzing mood trends over time.

* Theme Management
  Persistent dark/light mode using client-side state handling.

* Responsive Design
  Optimized for both desktop and mobile environments.

## Technology Stack

### Backend

* Python 3.12
* Flask
* Flask-SQLAlchemy
* Flask-SocketIO
* Flask-Mail

### Database

* SQLite (relational data storage for users, moods, and messages)

### Frontend

* HTML5
* CSS3 (custom styling with responsive design principles)
* JavaScript (Vanilla)
* Socket.IO Client
* Chart.js

### UI & Design

* Font Awesome
* Google Fonts (Poppins)
* CSS Variables (theme configuration and state persistence)

Run Locally

Clone the repository:

```bash
git clone https://github.com/nidhiless/mentally-swasth.git
cd mentally-swasth
```

Create virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## Project Structure

```
mentally-swasth
│
├── app.py
├── models.py
├── init_db.py
├── requirements.txt
│
├── templates
├── static
└── instance
```

---

## Author

**Nidhi Patel**

GitHub:
https://github.com/nidhiless
Mail:
nidhi.patel.builds@gmail.com

