# Flask Blog Project

This is a blog project built using Flask web framework.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run this project, you will need to have Python 3.x installed on your machine. You can download Python [here](https://www.python.org/downloads/).

### Installing

1. Clone the repository to your local machine using the command:

    ```
    git clone https://github.com/nick-rebrik/blog-flask.git
    ```

2. Navigate to the project directory using the command:

    ```
    cd blog-flask
    ```

3. Create a virtual environment using the command:

    ```
    python -m venv venv
    ```

4. Activate the virtual environment using the command:

    ```
    source venv/bin/activate
    ```

5. Install the required packages using the command:

    ```
    pip install -r requirements.txt
    ```

6. Create the database tables using the command:

    ```
    flask db upgrade
    ```

### Running the application

To run the application, execute the command:

    flask run

Open your web browser and go to `http://localhost:5000/` to view the application.

## Built With

* [Flask](https://flask.palletsprojects.com/) - The web framework used
* [SQLAlchemy](https://www.sqlalchemy.org/) - The database toolkit used

## Authors

* Nick Rebrik

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

