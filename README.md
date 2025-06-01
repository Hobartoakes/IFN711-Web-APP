# Device Information Query and Prediction System

A device information management system built with Flask, allowing users to register, log in, view, and add device details.

## Features

- User login and registration  
- Device information display and search  
- Add new devices  
- Support for exact purchase dates or estimated date ranges  

## Tech Stack

- Flask (Python web framework)  
- MySQL (database)  
- HTML/CSS  
- Tailwind CSS (utility-first CSS framework)  
- Font Awesome (icon library)  

## Installation and Running

1. Make sure Python and MySQL are installed.

2. Create the MySQL database:

    ```sql
    CREATE DATABASE device_management;
    ```

3. Install required Python packages:

    ```bash
    pip install flask pymysql
    ```

4. Run the application:

    ```bash
    python app.py
    ```

5. Open your browser and go to: [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Database Configuration

- Database name: `device_management`  
- Username: `root`  
- Password: `987654321`  

## Page Descriptions

1. **Login Page** – For existing users to log into the system  
2. **Registration Page** – For new users to sign up  
3. **Device Information Page** – Displays the list of devices and supports search  
4. **Add Device Page** – Allows users to add new device details
