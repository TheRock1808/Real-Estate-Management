# Real Estate Management System

## Overview
Welcome to the Real Estate Management System! This is a fully functional web application designed to facilitate the buying and selling of houses. The platform offers users a secure and intuitive interface to list properties, browse available homes, and manage their transactions efficiently.

## Features
- **User Authentication**: Secure user login and registration implemented using PHP Mailer.
- **User-Friendly Interface**: Frontend designed and styled using HTML, CSS, Bootstrap, and JavaScript.
- **Dashboard**: Users can manage their listings and messages efficiently from a dedicated dashboard.
- **Rating System**: Allows users to rate houses, helping others make informed decisions, particularly for rentals.
- **Navigation System**: Displays available houses at specified locations for easier navigation.

## Technologies Used
- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Email Authentication**: PHP Mailer

## Installation
### Prerequisites
- Web server (e.g., Apache)
- PHP (version 7.0 or higher)
- MySQL
- Composer (for PHP Mailer)

### Steps
# 1. Clone the Repository:
   ```bash
   git clone https://github.com/your-username/real-estate-management.git
   cd real-estate-management
   ```

# 2. Install Dependencies:
   ```bash
   composer install
   ```

# 3. Setup Database:
   - Create a MySQL database.
   - Import the database schema from `database/schema.sql`.
   - Update the database configuration in `config.php`:
     ```php
     define('DB_SERVER', 'your-database-server');
     define('DB_USERNAME', 'your-database-username');
     define('DB_PASSWORD', 'your-database-password');
     define('DB_NAME', 'your-database-name');
     ```

# 4. Configure PHP Mailer:
   - Update email configuration in `config.php`:
     ```php
     define('EMAIL_HOST', 'your-smtp-host');
     define('EMAIL_USERNAME', 'your-email-username');
     define('EMAIL_PASSWORD', 'your-email-password');
     define('EMAIL_PORT', 587); // or your SMTP port
     ```

# 5. Deploy the Application:
   - Move the project files to your web server's root directory (e.g., `/var/www/html` for Apache).
   - Ensure the server is configured to serve PHP applications.

# 6. Access the Application:
   - Open a web browser and navigate to your server's address (e.g., `http://localhost/real-estate-management`).

## Usage
- Register: Create a new account using the registration form.
- Login: Login to your account using the login form.
- Dashboard: Access your dashboard to manage listings and messages.
- Add Listings: Add new house listings with detailed descriptions and images.
- Rate Houses: Rate the houses you have viewed to help other users.
- Browse Listings: Use the navigation system to find available houses in specific locations.
