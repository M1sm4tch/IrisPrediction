# Django Iris Classification Project

This project contains a Django web application for predicting iris species using a pre-trained machine learning model.

## Project Setup

This guide will walk you through setting up a virtual environment, installing required packages, and running a Django server.

## Prerequisites

- Python 3.x installed on your system
- pip (Python package installer) installed

## Setup

1. Clone this repository to your local machine:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd <project_directory>
```

3. Create a virtual environment. Virtual environments allow you to isolate project dependencies:

```bash
python3 -m venv venv
```

4. Activate the virtual environment:

   - On Windows:

   ```bash
   venv\Scripts\activate
   ```

   - On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

5. Install required packages using pip. Make sure you're in the virtual environment:

```bash
pip install -r requirements.txt
```

## Running the Server

1. Make migrations for your Django project:

```bash
python manage.py makemigrations
python manage.py migrate
```

2. Create a superuser (admin) account:

    (you can use the current super user id= faraz_2, password=faraz)

```bash
python manage.py createsuperuser
```

3. Run the Django development server:

```bash
python manage.py runserver
```

The server will start running locally at http://127.0.0.1:8000/.

4. To access the Django admin panel, navigate to http://127.0.0.1:8000/admin/ and log in with the superuser credentials created earlier.

## Additional Notes

- Make sure to keep your virtual environment activated whenever you're working on the project.
- It's good practice to update the requirements.txt file whenever you install or update packages. You can do this by running:

```bash
pip freeze > requirements.txt
```

- Remember to deactivate the virtual environment when you're done working on the project:

```bash
deactivate
```

