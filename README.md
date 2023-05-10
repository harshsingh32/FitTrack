# FitTrack

FitTrack is a application that allows users to track their fitness progress, set fitness goals, and connect with other fitness enthusiasts. The app is built using the Flask web framework and it uses PostgreSQL as its database.

[🔗Project](https://fittclub.netlify.app/)

## Features

- User authentication and authorization
- Fitness tracking, including workouts, exercises, and progress tracking
- Goal setting and tracking
- Social networking features, including following other users, commenting on posts, and liking posts
- User profile management, including profile picture updates and password changes

## Technologies Used

- Flask web framework
- PostgreSQL database system
- SQLAlchemy ORM
- WTForms for form validation
- Bootstrap CSS framework
- FontAwesome icon library 

## Installation

To install and run FitTrack on your local machine, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory and create a virtual environment: `python3 -m venv venv`
3. Activate the virtual environment: `source venv/bin/activate`
4. Install the project dependencies: `pip install -r requirements.txt`
5. Create a PostgreSQL database and update the `config.py` file with your database credentials.
6. Run the database migrations: `flask db upgrade`
7. Start the Flask development server: `flask run`

The app should now be accessible at `http://localhost:5000`.


## Contributing

If you'd like to contribute to FitTrack, please follow these steps:

1. Fork the repository and create a new branch for your changes.
2. Make your changes and test the app locally.
3. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
