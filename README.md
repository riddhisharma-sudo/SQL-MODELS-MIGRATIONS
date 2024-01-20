# Django Flight Management App

## Overview

This Django project is a web application for flight management. It includes features for managing flights, origins, destinations, arrivals, and departures. The project uses SQLite as the database. Additionally, users can log in to view their specific flight details and explore other available flights.

## Features

- User Authentication: Allows users to register, log in, and log out securely.
- Flight Management: Admin can manage flights, origins, destinations, arrivals, and departures.
- User-Specific Flights: Upon login, users can view details about their flights.

## Technologies Used

- Django
- SQLite3

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd your-project
   ```

3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Run migrations:
   ```bash
   python manage.py migrate
   ```

7. Create a superuser for accessing the admin interface:
   ```bash
   python manage.py createsuperuser
   ```

8. Run the development server:
   ```bash
   python manage.py runserver
   ```

9. Access the application at [http://localhost:8000](http://localhost:8000).

## Usage

### Admin Interface

- To access the Django Admin interface, log in using the superuser credentials created earlier: [http://localhost:8000/admin](http://localhost:8000/admin).
- Manage flights, origins, destinations, arrivals, and departures through the admin interface.

### User-Specific Flights

- Users can register and log in using the application.
- After logging in, users can view details about their specific flights.
- Explore other available flights on the platform.

## License

This project is licensed under the [MIT License](LICENSE).

