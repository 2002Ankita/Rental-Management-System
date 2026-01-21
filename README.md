# 🏠 Rental Management System

## 📌 About the Project

The **Rental Management System** is a web-based application developed
using **Django and Django REST Framework** to manage rental properties,
bookings, and payments efficiently. The project provides a structured
backend solution where hosts can list properties and travelers can
browse, book, and manage rentals securely.

The system implements **role-based authentication** to control access
for different user types and uses **RESTful APIs** to handle booking
operations and integrate a third-party payment gateway. It follows the
**MVT architecture** and uses **Django ORM with SQLite** for reliable
database management.

This project demonstrates practical backend development skills such as
API design, authentication, database modeling, and real-world workflow
implementation.

------------------------------------------------------------------------

## 🚀 Features

-   User registration and authentication
-   Role-based access control (Host & Traveler)
-   Property listing and management
-   Property availability checking
-   Booking creation and status management
-   Secure payment gateway integration using REST APIs
-   Database operations using Django ORM

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python
-   Django
-   Django REST Framework
-   SQLite
-   REST APIs
-   Git & GitHub

------------------------------------------------------------------------

## 📂 Project Structure (High Level)

    rental_management/
    │── accounts/
    │── listings/
    │── bookings/
    │── payments/
    │── rental_management/
    │── manage.py

------------------------------------------------------------------------

## ⚙️ Installation & Setup

1.  Clone the repository

``` bash
git clone https://github.com/your-username/rental-management-system.git
```

2.  Navigate to the project directory

``` bash
cd rental-management-system
```

3.  Create a virtual environment and activate it

``` bash
python -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate
```

4.  Install dependencies

``` bash
pip install -r requirements.txt
```

5.  Apply migrations

``` bash
python manage.py migrate
```

6.  Run the development server

``` bash
python manage.py runserver
```

------------------------------------------------------------------------

## 🔑 API Usage

The project exposes RESTful APIs for:

-   User authentication
-   Property management
-   Booking operations
-   Payment processing

APIs are tested using tools like **Postman**.

------------------------------------------------------------------------

## 🎯 Learning Outcomes

-   Hands-on experience with Django REST Framework
-   Designing and consuming REST APIs
-   Implementing role-based authentication
-   Database modeling using Django ORM
-   Integrating third-party payment services

------------------------------------------------------------------------

## 📌 Future Enhancements

-   Frontend integration (React / HTML-CSS)
-   Advanced search and filtering
-   Email notifications for bookings
-   Deployment on cloud platforms

------------------------------------------------------------------------

## 👩‍💻 Author

**Ankita Kenjale**

------------------------------------------------------------------------

⭐ If you like this project, feel free to star the repository!
