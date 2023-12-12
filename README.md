This Project is inspired by Krish Naik youtube channel.

Steps to run on your system:-

# Navigate to your project directory (replace with your actual directory path)
cd path/to/your/project

# Create a virtual environment (optional)
python -m venv venv

# Activate the virtual environment

# On Windows
venv\Scripts\activate
# On Unix/macOS
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set Flask environment variables

# On Windows
set FLASK_APP=app.py
set FLASK_ENV=development

# On Unix/macOS
export FLASK_APP=app.py
export FLASK_ENV=development

# Run the application
flask run
