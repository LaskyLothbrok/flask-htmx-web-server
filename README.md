# Flask-HTMX Search App

This application is a Flask-based web app that allows users to search through a dataset loaded from a JSON file. It's designed to demonstrate the capabilities of HTMX by testing how much loaded data it can handle before breaking.

## Project Structure

- `app.py`: This is the main application file. It sets up the Flask application and handles the routing.
- `generate_data.py`: This script generates the data that the application uses. If `data.json` does not exist or is empty, this script is called to generate the data.
- `requirements.txt`: This file lists the Python dependencies that the project needs.
- `templates/`: This directory contains the HTML templates that the application uses.
  - `index.html`: This is the home page of the application.
  - `search_result.html`: This page displays the results of a search.
- `venv/`: This directory contains the Python virtual environment for the project.

## Setup and Running

1. Clone the repository:

```sh
git clone <repository-url>

cd <repository-name>

python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt

python app.py
