# EMAPI
Event Management API


# API Endpoints to Implement:

## User Endpoints:
POST /users/
Register a new user.
GET /users/<id>/
Retrieve user details.
PUT /users/<id>/
Update user details.
DELETE /users/<id>/
Delete a user.
Event Endpoints:
POST /events/

## Create a new event.
GET /events/<id>/
Retrieve event details.
PUT /events/<id>/
Update event details.
DELETE /events/<id>/

## Delete an event.
Upcoming Events:
GET /events/upcoming/
Retrieve a list of events that occur in the future.
Tools and Libraries to Use:
Backend Framework:
Django for core functionality and ORM.
Django REST Framework (DRF) for building the API.

# Database:

PostgreSQL (preferred for deployment) or SQLite (for local development).

# Authentication:
JWT Authentication using djangorestframework-simplejwt.
# Deployment Tools:
Heroku or PythonAnywhere for hosting.
Gunicorn for a WSGI server in production.
Whitenoise for serving static files on Heroku.
# Development Tools:
Postman or Insomnia for testing the API endpoints.
Git for version control.
# Others:
Black for code formatting.
Pytest for testing the API functionality.
