# Cloth-suggestion(PHP)

 A simple clothing Suggesting website based on purchased clothing, made with PHP.

## Overview

The Simple Clothing Suggesting Website (PHP) is an online platform designed to provide clothing recommendations based on user preferences. Users can input their style choices, and the website will suggest outfits or individual clothing items to match their preferences.

## Features

- User Registration and Authentication
- Style Preference Selection
- Clothing Category Filtering
- Personalized Clothing Recommendations
- Search Functionality
- User Profile Management

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
- Web Server: Apache or Nginx
- Bootstrap (optional)

## Installation

### Prerequisites

- Web server with PHP support (e.g., Apache, Nginx)
- MySQL database
- Web browser

### Steps

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/TAMILMANI-11/clothing-suggesting-website-php.git
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd clothing-suggesting-website-php
    ```

3. **Import the Database Schema:**

   - Create a MySQL database for the application.
   - Import the database schema from `database/schema.sql`.

    ```bash
    mysql -u your_username -p your_database_name < database/schema.sql
    ```

4. **Configure Database Connection:**

    Update the database configuration in `config/database.php` with your database credentials:

    ```php
    return [
        'driver'   => 'mysql',
        'host'     => 'localhost',
        'database' => 'your_database_name',
        'username' => 'your_username',
        'password' => 'your_password',
        // ...
    ];
    ```

5. **Run the Application:**

    Start your PHP-enabled web server:

    ```bash
    php -S localhost:8000 -t public
    ```

    The application should now be running on `http://localhost:8000`.

6. **Access the Application:**

    Open your web browser and navigate to `http://localhost:8000`.

7. **User Registration:**

    - Register an account to start using the website.
    - Provide style preferences during the registration process.

8. **Explore Clothing Recommendations:**

    - Log in and explore personalized clothing recommendations.
    - Use the search functionality and apply category filters.

9. **Profile Management:**

    - Update your style preferences in the user profile section.
