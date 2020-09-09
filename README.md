# Django-Chime

## Prerequistes:

- Ensure you have Python 3.7 or greater installed. You can opt to set up a virutal environment or a conda enviroment.
- Make sure pip works with the python installation

## This project demonstrates a deployment of Amazon Chime on a Django server

The steps to run this project are as follows:

1. Clone this repository to the local system.
2. Run 'pip install -r requirements.txt' from the project root.
3. Add the absolute path to the project directory to the PYTHONPATH environment variable on your local system. 
  (Instructions for Windows: [here](https://stackoverflow.com/questions/3701646/how-to-add-to-the-pythonpath-in-windows-so-it-finds-my-modules-packages) | For Mac/Linux the following command should work: export PYTHONPATH=/path/to/django_chime where /path/to/django_chime is the absolute path to the django_chime project)
4. Run 'python -m pip install Django' from the project root directory to install Django.
5. Execute 'python manage.py runserver 8000' to run the development server.