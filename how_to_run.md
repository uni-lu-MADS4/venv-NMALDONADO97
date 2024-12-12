# How to Run the Project

## You have to do all the steps in the windows powershell!!!! 

# Step 1: Clone the Repository
# Use the following commands to download the project to your computer and navigate into the project folder:
git clone https://github.com/uni-lu-MADS4/venv-NMALDONADO97.git # Use this for Windows PowerShell 
cd venv-NMALDONADO97 # Use this for Windows PowerShell 

# Step 2: Create a Virtual Environment
# This creates an isolated environment for the project, so dependencies won't interfere with your system.
python -m venv venv # Use this for Windows PowerShell 

# Step 3: Activate the Virtual Environment
# Depending on your system, use one of the following commands:

# For Windows PowerShell, you may need to allow scripts to run:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

# Then activate the virtual environment:
.\venv\Scripts\Activate.ps1  # Use this for Windows PowerShell

# For Mac/Linux:
source venv/bin/activate  # Use this command on Mac/Linux systems

# Step 4: Install the Required Dependencies
# Install all the Python packages listed in the requirements.txt file:
pip install -r requirements.txt # Use this for Windows PowerShell 

# Step 5: Run the Python Script
# Replace Q06.py with the name of your Python script and run it:
python Q06.py # Use this for Windows PowerShell 
