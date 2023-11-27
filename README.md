# Smart Coaster with POS and Payment System

The Smart Coaster System, initially developed by Enzo and Robert, revolutionizes the dining experience by providing customers with seamless access to their food orders and empowering restaurants with efficient order management. Fischbach and Frenker-Hackfort have taken on the task of enhancing this system, focusing on integrating payment options and connecting it to Point of Sale (POS) systems.

## Project Summary

The Smart Coaster System, developed by Enzo and Robert, allows customers to view their food orders by scanning a QR code on the coaster. Simultaneously, the system tracks drink orders by measuring the glass's weight and notifies the restaurant when a refill is needed. Fischbach and Frenker-Hackfort aim to improve this system by integrating payment options and connecting it to various POS systems used by different restaurants.

## Project Goals

1. **Enhance Smart Coaster's Capabilities:**
   - Enable direct payments through the Smart Coaster for increased customer convenience.
   - Seamlessly integrate the Smart Coaster with different POS systems to streamline restaurant operations.

2. **Improve User Experience:**
   - Simplify the billing process by allowing users to make payments directly through the Smart Coaster.
   - Reduce reliance on waitstaff, saving time for both customers and restaurant staff.

## Setup Instructions

To set up the Django project:

1. Designate the desired directory for the project.
2. Install a virtual environment:
   - Unix-based systems: '''source venv/bin/activate'''
   - Windows: '''venv\Scripts\activate\'''
3. Install project requirements: \`pip install -r requirements.txt\`

## Admin Portal

1. Create a superuser account: \`python manage.py createsuperuser\`
2. Synchronize changes with the database: \`python manage.py migrate\` and \`python manage.py makemigrations\`
3. Access the admin portal at [http://localhost:8000/admin](http://localhost:8000/admin)

The admin portal allows efficient management of database records and essential administrative tasks.

## Navigating the User Interface

1. Launch the development server: \`python manage.py runserver\`
2. Access the homepage at [http://localhost:8000/](http://localhost:8000/)
3. Visit [http://localhost:8000/overview](http://localhost:8000/overview) for a monitoring page displaying requests from Smart Coasters.
4. Explore [http://localhost:8000/table](http://localhost:8000/table) for a comprehensive view of all tables.
5. Access individual Smart Coaster orders and make payments directly using the integrated PayPal system and receive the recipt/bill after successful payment which can be download as PDF file.

This system provides a user-friendly interface for configuring and overseeing the Smart Coaster system within a restaurant environment.
