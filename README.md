# Django CRUD Project with User Authentication

This is a Django project that demonstrates basic CRUD (Create, Read, Update, Delete) operations and includes user authentication for user login and logout.

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone the repository:

```
git clone https://github.com/Prakharjain1211/Django-CRUD-AUTH-Project.git
```


2. Navigate to the project directory:

```
cd django-crud-auth-project
```


3. Create a virtual environment (optional but recommended):

```
python -m venv venv
source venv/bin/activate (Linux/Mac) or venv\Scripts\activate (Windows)
```


4. Install project dependencies:

```
pip install -r requirements.txt
```


5. Migrate the database:

```
python manage.py migrate
```

6. Create a superuser for admin access:

```
python manage.py createsuperuser
```


7. Run the development server:

```
python manage.py runserver
```


8. Access the application in your browser at [http://localhost:8000/](http://localhost:8000/)

## Features

**User Authentication**:
- User registration
- User login
- User logout
- Access control (only authenticated users can perform CRUD operations)

**CRUD Operations**:
- Create new items
- Read items
- Update items
- Delete items

## Project Structure

The project structure is organized as follows:

- `myapp/` - Django app for CRUD operations
- `accounts/` - Django app for user authentication
- `templates/` - HTML templates for the user interface
- `static/` - Static files like CSS and JavaScript
- `manage.py` - Django management script
- `settings.py` - Django project settings
- `urls.py` - URL routing for the project

## Usage

  - Register a new user account or use the superuser account  created during setup.
 - Log in to access the CRUD functionality.
 - Create, read, update, or delete items as needed.

## Dependencies
 
- Django==2.2.5
- djangorestframework==3.10.3
- pytz==2019.2
- sqlparse==0.3.0
- python==3.73

## Screenshots of the Project
- Home Page
![Home Page](https://github.com/Prakharjain1211/Django-CRUD-AUTH-Project/assets/88723250/55ba8e35-2a03-4ab6-8198-f5f8efecdb9a)

## Contributing

Feel free to contribute to this project by opening issues or pull requests on the GitHub repository.

## Acknowledgments

- Thanks to the Django community for providing a powerful web framework.
- This project is for educational purposes and can be used as a starting point for your Django applications.


