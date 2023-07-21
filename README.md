# Interpreter
A flask app for translation using Azure cognitive AI translator API.

## Development Server
First create virtual environment using `python -m venv venv`. Activate the environment by `.\venv\scripts\activate`.
Then install requirements. Run `python3 -m pip install requirements.txt`. Then run `set FLASK_ENV=development`, this will ensure that  the server will automatically reload with every change.
Run `python3 -m flask run` for a dev server. Navigate to `http://localhost:5000`.
