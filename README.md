# Django REST API Project

This project is a RESTful API developed using the Django REST Framework. It also uses Djoser for user authentication and management. The project uses SQLite as the database.

## Features

- **Rendering**: The API supports multiple rendering formats including JSON, Browsable API, XML, CSV, and YAML.
- **Filtering**: The API uses Django Filter Backend for filtering results, along with OrderingFilter and SearchFilter for sorting and searching.
- **Pagination**: The API uses PageNumberPagination for paginating results, with a page size of 3.
- **Authentication**: The API uses TokenAuthentication and SessionAuthentication for user authentication.
- **Throttling**: The API uses AnonRateThrottle and UserRateThrottle for rate limiting, with rates set for anonymous users (2 requests/minute), authenticated users (5 requests/minute), and a custom rate (10 requests/minute).
- **User Management**: The API uses Djoser for user management, with the username field used as the user ID.
- **Database**: The project uses SQLite as the database.

## Setup

To set up this project, you will need to install Django, Django REST Framework, and Djoser. You can do this using pip:

Then, clone this repository and navigate into the project directory. You can start the server using the following command:
`python manage.py runserver`

Usage
You can interact with the API using any HTTP client like curl, Postman, or Insomnia. The API supports standard HTTP methods like GET, POST, PUT, PATCH, and DELETE.

Contributing
Contributions are welcome! Please read the contributing guidelines before making any changes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.