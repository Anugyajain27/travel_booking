# Travel Booking Web App

This is a Django-based web application that allows users to register, log in, search for travel options (by type, city, or date), book seats, view their bookings, and cancel if needed. It also features an admin panel for managing travel data.

---

## 🔗 Live Demo

You can access the live deployed application here:
 https://anugyajain27.pythonanywhere.com

---

##  Tech Stack

| Layer       | Technology                            |
|-------------|----------------------------------------|
| Backend     | Python 3.11, Django 5.2.4              |
| Frontend    | HTML5, CSS3, Bootstrap 5               |
| Database    | SQLite (for deployment)                |
| Auth        | Django's built-in user authentication  |
| Deployment  | PythonAnywhere                         |

---

##  Features

-  User registration, login & logout
-  Search & filter travel options by:
  - Travel Type (Flight / Train / Bus)
  - Source & Destination
  - Travel Date
-  Book seats with dynamic availability
-  View & manage bookings
-  Cancel bookings with seat restoration
-  Admin panel for managing travel options

---

##  Setup Instructions (For Local Use)
 
1. Clone the project
```bash
git clone https://github.com/Anugyajain27e/travel_booking.git
cd travel_booking
python -m venv venv
venv\Scripts\activate  # On Windows
# or
source venv/bin/activate  # On Mac/Linux

2. Install dependencies
```bash
Copy
Edit
pip install -r requirements.txt
If not available, manually install:

bash
Copy
Edit
pip install django pymysql
4. Run migrations
bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
5. Create a superuser (admin)
bash
Copy
Edit
python manage.py createsuperuser
6. Run the development server
bash
Copy
Edit
python manage.py runserver
Then open http://127.0.0.1:8000


Deployment Notes
The app is deployed on PythonAnywhere

SQLite is used for database in the deployed version

Allowed host is restricted to: anugyajain27.pythonanywhere.com

To access admin panel:

 https://anugyajain27.pythonanywhere.com/admin
(Login with your superuser credentials)
