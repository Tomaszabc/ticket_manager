# Ticket Manager

Ticket Manager is a Django-based web application designed to manage tickets efficiently. This project utilizes Tailwind CSS for styling, providing a modern and responsive user interface.

## Project Structure

```
ticket-manager
├── ticket_manager
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
├── app
│   ├── migrations
│   │   └── __init__.py
│   ├── static
│   │   ├── css
│   │   └── js
│   ├── templates
│   │   └── index.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── manage.py
├── package.json
├── tailwind.config.js
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd ticket-manager
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Install npm dependencies:
   ```
   npm install
   ```

## Usage

1. Run migrations:
   ```
   python manage.py migrate
   ```

2. Start the development server:
   ```
   python manage.py runserver
   ```

3. Open your browser and navigate to `http://127.0.0.1:8000/` to view the application.

## Features

- User-friendly interface with a navigation bar.
- Responsive design using Tailwind CSS.
- Easy management of tickets.

## Contributing

Feel free to submit issues or pull requests to improve the project. 

## License

This project is licensed under the MIT License.