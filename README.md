# LAB6-Data-Management
MNHS APP: A Flask-based healthcare management system for managing patients, appointments, staff, and hospital inventory.

Patient Management: View and list patients ordered by last name
Appointment Scheduling: Schedule clinical appointments with staff and departments
Inventory Tracking: Monitor medication stock levels and identify low-stock items
Staff Analytics: Calculate appointment distribution and workload per staff member across hospitals

Technologies Used
Backend: Python 3.x, Flask 2.3.3
Database: MySQL 8.x
Environment Management: python-dotenv

Available Routes:
/ - Home page
/patients - View all patients
/schedule - Schedule new appointments
/low_stock - View low stock medications
/staff_share - View staff appointment distribution

.Project Structure:
├── app.py                      # Flask web application
├── cli.py                      # Command-line interface
├── db_connection.py            # Database connection configuration
├── list_patients.py            # Patient listing functionality
├── schedule_appointment.py     # Appointment scheduling logic
├── low_stock.py               # Inventory tracking
├── staff_share.py             # Staff analytics
├── requi.txt                  # Python dependencies
├── templates/                 # HTML templates
├── .env.example              # Environment variables template
└── .gitignore                # Git ignore file
├── static/                    #css file


