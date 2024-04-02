## Building a RESTful API with Flask - Error Handling, Authentication,and File Handling with Public and Admin Routes

## Project Team Members - Group Mid Term Project 7
1. Venkata Abhinav Karthik Pulikonda (Cwid -885210294)
2. Sai Satya Jagannadh Doddipatla (Cwid - 885177436)

## Drive Link For the Project Demonstration and Screenshots - 

https://drive.google.com/drive/folders/1_-bRyxBzG-MOBr7oRufE9ql5LMYafkMC?usp=sharing

## Project Description

RESTful API using Flask that covers error handling, authentication, and file handling. The API will have two types of routes - public routes that can be accessed without authentication and protected admin routes that require authentication.A Flask project that includes JWT (JSON Web Token) implementation. The project is written in Python version 3.11.5 and is designed to provide a template for creating a Flask-based API with JWT authentication. This readme will guide you through the process of setting up and running the project.

## Getting Started

Follow these steps to set up and run the Flask project with JWT implementation:

1. **Clone or Download the Project**: Clone this project repository or download the project files and extract them to a directory of your choice.Also Download the project required packages from the "requirements.txt" file and ensure you have the update python version installed before running the application.

2. **Activate the Virtual Environment**: Navigate to the project directory in your terminal or bash and activate the virtual environment. You can do this by running the following command:

   ```bash
   source venv/bin/activate
   ```

   Activating the virtual environment is important to ensure you are using the correct dependencies for the project.

3. **Configure the Database**:
   - Open the `.env` file in your project directory.
   - Locate the `DATABASE_URL` variable and replace it with your MySQL database connection URL. For example:

   ```plaintext
   DATABASE_URL=mysql://username:password@localhost/database_name
   ```

4. **Initialize the Database**:
   Run the following commands to initialize and apply database migrations:
   
   - Initialize the database instance:
     ```bash
     flask db init
     ```

   - Create a migration with a description (e.g., "Database migrations"):
     ```bash
     flask db migrate -m "Database migrations"
     ```

   - Apply the changes to the database:
     ```bash
     flask db upgrade
     ```

5. **Run the Project**:
   To start the Flask application, run the following command:

   ```bash
   python app.py
   ```

   This will start the project, and it will be accessible at `http://127.0.0.1:5000` or `http://localhost:5000`.

## API Access

You can access the API by making HTTP requests to the following URL:

- `http://127.0.0.1:5000`

The project is now set up and ready for you to develop your own endpoints and functionality.

## Important Notes

- Make sure you have Python 3.11.5 or a compatible version installed.

- Ensure you have MySQL database credentials and a database created before updating the `.env` file.

- It's recommended to use a tool like Postman or curl to interact with the API and test the JWT authentication.

- Remember to deactivate the virtual environment when you're done with the project:

  ```bash
  deactivate
  ```

## Additional Resources

For more information about Flask and JWT, consult the following resources:

- Flask documentation: [https://flask.palletsprojects.com/](https://flask.palletsprojects.com/)
- Flask-Migrate documentation: [https://flask-migrate.readthedocs.io/en/latest/](https://flask-migrate.readthedocs.io/en/latest/)
- Flask-JWT documentation: [https://pythonhosted.org/Flask-JWT/](https://pythonhosted.org/Flask-JWT/)

You are now ready to start working on your Flask project with JWT authentication.
