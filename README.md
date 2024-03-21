# Renter

Renter is a comprehensive property rental website built with PHP and MySQL, designed to facilitate property listings and bookings across Goa. This README provides an overview of the project, its features, and instructions for setting up and running the application.

PDF showing the list of Modules other than Authentication below:
[Modules.pdf](https://github.com/Droovian/Renter-DBMS-Project/files/14622540/Modules.pdf)

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features

### Authentication
- User-friendly authentication system with features such as login, signup, and forgot password.
- OTP verification for enhanced security.
- Integration with PHPMailer for email communication.

### Listings Module
- Property owners can list their properties on the platform.
- Listing approval process managed by the founder.

### Bookings Module
- Seamless booking experience for users.
- Integration of Razorpay API (test) for secure payment transactions.

### GIS Implementation
- Utilizes Leaflet JS for interactive map functionality.
- API integration for a comprehensive geographical information system.

### Reviews Module
- Customers can leave reviews for properties after their bookings as well as request for cancellation.

## Requirements
- PHP (>= 7.0)
- MySQL
- XAMPP or similar web server environment
- Composer (for PHPMailer)
