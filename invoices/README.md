# Invoice Generator

This is a full stack web application for generating and managing invoices. The application uses Next.js for the frontend and Django for the backend. Users can register, login, generate invoices, and view their invoice history.

## Features

- User registration and login
- Invoice generation and management
- Responsive user interface
- RESTful API using Django REST framework
- JWT-based authentication

## Getting Started

To get started with the project, you'll need to have Node.js, Python 3, and Django installed on your machine. Then follow these steps:

1. Clone the repository to your local machine.
2. Install the dependencies by running `npm install` in the frontend directory and `pip install -r requirements.txt` in the backend directory.
3. Create a `.env.local` file in the frontend directory and add the following environment variables:

    ```
    NEXT_PUBLIC_API_BASE_URL=http://localhost:8000/api/
    ```

4. Create a `.env` file in the backend directory and add the following environment variables:

    ```
    SECRET_KEY=<your_secret_key>
    DEBUG=True
    ALLOWED_HOSTS=localhost
    ```

5. Create the database by running `python manage.py migrate` in the backend directory.
6. Start the frontend server by running `npm run dev` in the frontend directory.
7. Start the backend server by running `python manage.py runserver` in the backend directory.
8. Open your browser and navigate to `http://localhost:3000` to use the application.

## Contributing

Contributions are welcome! To contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your fork.
5. Create a pull request to the main repository.



## Author

This project was created by [Your Name Here]. Contact me at bilimdepaullilian@gmail.com.
