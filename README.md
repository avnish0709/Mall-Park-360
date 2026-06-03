
# Mall-Park-360

A comprehensive parking management system designed for shopping malls with role-based dashboards for *Parking Supervisors*, *Parking Officers*, and *Parking Lot Attendants*. 

---

- Features

- **Role-Based Access Control**
  - Parking Supervisors: Full dashboard with analytics and reporting
  - Parking Officers: Monitoring and enforcement
  - Parking Lot Attendants: Slot management and configuration

- **Parking Slot Management**
  - Real-time slot availability tracking
  - Multi-floor and multi-pillar organization
  - Dynamic slot reservation and release
  - Vehicle tracking and parking history

- **Financial Management**
  - Automated ticket generation and payment processing
  - GST (Goods and Services Tax) calculation
  - Revenue analytics and income reports
  - Daily statistics and earnings tracking

- **Real-Time Updates**
  - WebSocket-based live slot updates
  - Instant notification system for all connected clients
  - Synchronized parking status across all interfaces

- **Comprehensive Reporting**
  - Daily parking statistics
  - 7-day income analytics with charts
  - Ticket history and management
  - Payment tracking

---

## Tech Stack

| Component | Technology |
|-----------|-----------|
| **Backend** | Python 3, Flask, Flask-SocketIO |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Database** | SQLite3 |
| **Real-time Communication** | WebSockets (Socket.IO) |
| **API** | RESTful API |
| **Server** | Uvicorn / Gunicorn |
| **Dependencies** | FastAPI, python-multipart |

---


## Project Structure

```bash
Mall-Park-360/
│
├── app.py                  # Main Flask application
├── Requirements            # Python dependencies
├── Setup                   # Installation scripts 
├── Contribution.md         # Contribution 
├── LICENSE                 # MIT License
├── mallpark360.db          # SQLite database 
│
├── static/                 # Frontend files
│   ├── index.html          # Login page
│   ├── supervisor.html     # Parking Supervisor dashboard
│   ├── officer.html        # Parking Officer dashboard
│   ├── attendant.html      # Lot Attendant dashboard
│   └── ticket.html         # Ticket view
│
└── README.md               # Project documentation
```

---

## Installation


### Prerequisites

- Python 3.8 + 
- pip 
- SQLite3 

### Step 1: Clone the Repository

```bash
git clone https://github.com/avnish0709/Mall-Park-360.git
cd Mall-Park-360
```

### Step 2: Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```
