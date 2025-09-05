# Creates a new virtual environment in the .venv directory
python -m venv .venv

# Activate the Virtual Environment
source .venv/bin/activate

# lists all the dependencies and save
pip freeze > requirements.txt

# Install packages 
pip install -r requirements.txt
pip install *dependencies*

# Set Environment varable
export EnvVariable=EnvValue

# Runs Python script in the virtual environment
python main.py

# Deactivate the Virtual Environment
deactivate
