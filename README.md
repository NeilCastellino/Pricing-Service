# Pricing-Service
Pricing Service is a python application that would help you keep a track of an online store item that you desire to purchase and inform you via an email when the price reduces to a certain mentioned limit.  
This application uses python 3 and mongoDB    
This application works well for www.johnlewis.com and not for amazon or flipkart because I would need access permissions.

## How to run
Step 1: Download the code  
Step 2: Open a terminal and navigate to the folder outside the main code folder ie. src  
Step 3: Run this command
```
virtualenv venv
```
Step 4: Navigate to venv\Scripts and type (Only for Windows users)
```
activate.bat
```
Step 5: Navigate back to code and type
```
python --version
```
You should be able to see the version of python that is installed.  
Step 6: Install other libraries
```
pip install flask datetime bs4 werkzeug passlib pymongo uuid
```
Step 7: Run the app
```
python run.py
```

