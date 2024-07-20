# CRUD WEB APP USING PYTHON, DJANGO, AND MYSQL

<img src="https://images.unsplash.com/photo-1718414738167-0dd5de626229?q=80&w=870&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Quote" width="500" height="300"/>

## Welcome
Welcome to the CRUD Web Application project! This project demonstrates a simple and effective way to create a CRUD (Create, Read, Update, Delete) web application using Python, Django, and MySQL.

## Features
- **Create:** Add new records to the database.
- **Read:** View and retrieve existing records.
- **Update:** Modify existing records.
- **Delete:** Remove records from the database.

## Installation

### Prerequisites
- Python 3.x
- Django
- MySQL

### Steps
1. **Clone the repository:**
    ```bash
    git clone https://github.com/tu_usuario/crud-web-app.git
    cd crud-web-app
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Configure the database:**
    - Open `crud_app/settings.py`
    - Update the `DATABASES` section with your MySQL configuration:
      ```python
      DATABASES = {
          'default': {
              'ENGINE': 'django.db.backends.mysql',
              'NAME': 'your_database_name',
              'USER': 'your_database_user',
              'PASSWORD': 'your_database_password',
              'HOST': 'localhost',   # Or the address of your database server
              'PORT': '3306',        # Or the port your database server is using
          }
      }
      ```

5. **Apply migrations:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

## Usage
1. **Access the web application:**
   Open your web browser and go to `http://127.0.0.1:8000/`.

2. **Perform CRUD operations:**
   - Use the web interface to create, read, update, and delete records.

## Contributing
I welcome contributions to improve this project! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details on our code of conduct and the process for submitting pull requests.

## License
This project is not licensed

## Acknowledgements
- Photo by [Photographer's Name](https://unsplash.com/@photographer) on Unsplash

## Contact
If you have any questions or suggestions, feel free to open an issue or contact me directly at [alhexmbs@gmail.com](mailto:alhexmbs@gmail.com).

Thank you for checking out the CRUD Web Application project! I hope you find it useful and educational.
