# Django Style Guide Cookiecutter

Welcome to the **Django Style Guide** Cookiecutter template! This project is based on the [HackSoftware Django Styleguide](https://github.com/HackSoftware/Django-Styleguide) and provides a structured way to start new Django projects following best practices.

## Usage

### Prerequisites

Before you begin, make sure you have the following installed:

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. **Install Cookiecutter**

   ```bash
   pip install cookiecutter
   ```

2. **Setup the Project**

   Run the following command to create a new Django project using this template:

   ```bash
   cookiecutter https://github.com/alidanial7/django_style_guide.git
   ```

### Customization

During the setup process, you will be prompted to provide some details about your project. This includes:

- Project name
- Author name
- Email address
- Django version
- Database configuration (e.g., PostgreSQL, SQLite)

Feel free to customize these settings according to your preferences.

### Getting Started

Once the project is created, navigate to the project directory and start developing your application:

```bash
cd <your-project-name>
```

You can now run the development server:

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your web browser to see your new Django project in action.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue on the [GitHub repository](https://github.com/alidanial7/django_style_guide).

## License

This project is licensed under the MIT License.
