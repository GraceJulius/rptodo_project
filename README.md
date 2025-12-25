# rptodo_project

## yapping 
For this project, I built a CLI To-Do application using python and typer. This is more like a follow along with the Real Python tutorial as I am trying to understand python and more tools surrounding it deeper. I learned how to add commands, arguments, and options to the to-do application using Typer. I also got to test the to-do application using Typer’s CliRunner and pytest in Python. I got to practice working with JSON files using python json module and managing configuration files with Python’s configparser module.

I believe this is the beginning of greatness because this is the first project I am working on as I take my learning and career serious. I hope for the best from here on.

Enough of my yapping now to the serious part.



# Running the Application

RP To-Do is a Python command-line application built with Typer. Follow the steps below to run it locally.

Prerequisites

Python 3.10+

git

# Clone the Repository
git clone git@github.com:your-username/rptodo_project.git
cd rptodo_project

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # Linux / macOS

# Install Dependencies
pip install -r requirements.txt

# Run the CLI
Run the application as a Python module:
python -m rptodo --help

# Initialize the To-Do Database
To create the configuration file and database:
python -m rptodo init

# Check the Application Version
python -m rptodo --version

pip

(Recommended) a Python virtual environment
