# E-Commerce Website with Email Verification and Payment Integration

Welcome to our E-Commerce project! This is a Django-based web application that allows users to browse and purchase products. It incorporates user registration with email verification, a shopping cart, and a secure payment gateway. Read on to learn more about how to set up and use this project.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Features

- User Registration:
  - Users can create an account with their email and password.
  - An email verification link is sent to the user's email address.
  - Users can log in only after verifying their email.

- Shopping:
  - Users can view a list of available products on the homepage.
  - Products can be added to the shopping cart.
  - The cart can be cleared of items.

- Checkout and Payment:
  - Users can proceed to checkout with items in their cart.
  - A secure payment gateway is used for processing payments.
  - Users receive a confirmation upon successful payment.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your system.
- [Django](https://www.djangoproject.com/download/) framework installed.
- A text editor or integrated development environment (IDE).
- Internet access for email verification and payment processing.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/e-commerce-website.git
```

2. Create a Django superuser:

```bash
python manage.py createsuperuser
```

3. Apply the database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

4. Start the development server:

```bash
python manage.py runserver
```

5. Access the admin interface at `http://localhost:8000/admin/` and log in with your superuser credentials to add products.

## Usage

1. Open your web browser and go to `http://localhost:8000` to access the homepage.

2. Register a new user account and an email verification link will be sent to your email address.

3. Verify your email by clicking on the link in the email.

4. Log in to your account.

5. Browse the available products, add items to your cart, and proceed to checkout.

6. Complete the payment process using a secure payment gateway.

7. Upon successful payment, you will receive a confirmation.
