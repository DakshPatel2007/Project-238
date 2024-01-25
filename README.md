# Project-238
1. Manage.py manages how the application will run. It uses the flask group libraries. There are three functions; recreate_db, seeder and rsd. "recreate_db" resets the database and "seeder" will add the data into the database after it has been reset. "rsd" calls the recreate_db and seeder functions.

2. __init__.py is used to initiate the folder. When many folders are inside a folder, each folder acts as an application and needs __init__.py to initialise the folder.

3. views.py and api.py contain the front-end and back-end respectivly.

4.models.py is used to create the models of the database and its datatypes.
