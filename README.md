# HealthStack
Healthstack is an internet platform that supports numerous hospitals. It offers urgent medical aid to those in need of emergency care. Its capability of tracking, monitoring, and sharing a patient's health records across all hospitals. Patients can also view information about various hospitals and providers and schedule appointments online.
## Tools used:
      1) Programming Language and Libraries: Django (Python web framework), Bootstrap, JavaScript, Ajax, Django REST framework.
      2) Database: SQLite
      3) APIs used: MailTrap, Django PDF library, Django channels for chat, ngrok HTTP, PyPI packages.
      
## Features
### Patient
      1)  Search multiple Hospital → Department List → Search for Doctors
      2)  Doctor Profile → Book Appointment
      3)  Pay Appointment + Mail Confirmation 
      4)  Search all Doctors in all hospitals
      5)  Chat with appointed Doctor
      6)  View Prescription, Download Prescription (PDF)
      7)  Choose which tests to pay (Cart System, payment + mail confirmation)
      8)  View Report, Download Report (PDF)
      9)  Give Doctor Review
      10) Search for Medicines in Medical Shop (Pharmacy)
      11) Select which medicines to purchase (Cart system), pay total amount for medicines (payment + mail confirmation)
      
### Doctor 
      1)  Doctor Profile Settings (Add More feature)
      2)  Search multiple Hospital → Doctor register to hospital + upload certificate
      3)  (Once registered by admin) accept or reject patients appointment (mail confirmation send to patient)
      4)  Search patient profile → Create and view Prescription, view report
      5)  Chat with appointed Patient
      
### Hospital Admin
      1)  Admin Dashboard
      2)  Accept or reject doctor registration (view doctor profile to see details)
      3)  CRUD Hospitals (Add more)
      4)  View Hospital List → CRUD Departments within hospital
      5)  CRUD Lab Worker
      6)  CRUD Pharmacist

### Lab worker
      1)  Lab Worker Dashboard
      2)  Create Report for patient.
      3)  Create Tests for hospitals, View Tests

### Pharmacist
      1)  Pharmacist Dashboard
      2)  CRUD Medicines
      3)  Search Medicine


## Steps to start the app
      1) Start python virtual env
            pip install pipenv
      2) Activate the virtual environment 
            pipenv shell
      3) Install python pip paclages
            pipenv install
      4) Create .env from  .env.example and add secret key
            cp .env.example .env
      5) Upgrade django framework
            pip install --upgrade djangorestframework-simplejwt
      6) Migrate DB 
            python manage.py migrate
      7) Start the application
            python manage.py runserver


### Thank you for Reading If you have any doubt or suggestion please mail me.
