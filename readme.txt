File Structure

    run.py: This is the application's entry point. We'll run this file to start the Flask server and launch our application.
    
    config.py: This file contains the configuration variables for your app, such as database details.
    
    app/__init__.py: This file intializes a Python module. Without it, Python will not recognize the app directory as a module.
    
    app/views.py: This file contains all the routes for our application. This will tell Flask what to display on which path.
    
    app/models.py: This is where the models are defined. A model is a representation of a database table in code. 

Set Environment variables in Windows
$env:FLASK_CONFIG="development/production"
$env:FLASK_APP="run.py" our app name

run the project by calling app fuction
flask run
