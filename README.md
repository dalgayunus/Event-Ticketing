Event Ticketing

A web-based event ticketing system built with Python, Django, and Django REST Framework.

The project provides functionality for user management, authentication, event management, ticket management, orders, reviews, promo codes, and wallet-based payments.

Features

* User registration and authentication
* Email-based account activation
* JWT authentication
* User profile management
* Event creation and management
* Ticket management
* Event categories
* Event search and filtering
* Pagination and ordering
* Promo codes and discounts
* Order creation and management
* Wallet-based payments
* Refund functionality
* Event reviews and ratings
* PDF ticket generation
* QR-code ticket validation
* Email delivery of tickets
* Role-based permissions

Technologies

* Python
* Django
* Django REST Framework
* PostgreSQL
* Simple JWT
* Django Filter
* drf-yasg
* ReportLab
* Pillow
* QR Code

API Documentation

The project uses "drf-yasg" to generate API documentation.
After starting the development server, the configured Swagger and Redoc endpoints can be used to explore and test the API.

Authentication

The application uses JWT-based authentication.
Users can register, activate their accounts using an email verification code, log in, and manage their authentication tokens.

Events and Tickets:

Users can browse available events and tickets through the API.
Events support search, filtering, ordering, and pagination.

Orders and Payments:

Users can create orders for event tickets and pay using their wallet balance.
After a successful order, the system generates a PDF ticket and sends it to the user's email address.
Cancelled orders can be refunded to the user's wallet.

Installation:

Clone the repository:
git clone https://github.com/dalgayunus/Event-Ticketing
cd event-ticketing-backend

Create a virtual environment: python -m venv venv
Activate the virtual environment.

Windows:

venv\Scripts\activate

macOS/Linux:

source venv/bin/activate
Install the dependencies: pip install -r requirements.txt
Create a ".env" file and configure the required environment variables.
Apply database migrations: python manage.py migrate
Run the development server: python manage.py runserver

Environment Variables:

The project uses environment variables for configuration and sensitive information.
Refer to ".env.example" for the required variables.

Project Structure:

event-ticketing/
├── event/
├── user/
├── config/
├── manage.py
├── requirements.txt
├── .env.example
└── README.md

Future Improvements:

* Online payment integration
* Dedicated frontend application
* Production deployment
* Expanded automated test coverage

Author:

Dalga Yunus,
GitHub: https://github.com/dalgayunus
