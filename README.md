# djangogirl-coach guide

## Install Python Dependencies :
### GitHub Codespaces comes with Python pre-installed. Check the version by running:
```
python --version
```

### Set Up a Virtual Environment
```
python -m venv venv
```

On Linux/Mac:
```
source venv/bin/activate
```

On Windows:
```
venv\Scripts\activate
```

### Install Django 
```
pip install django
```

### Start Django Project
#### Create a New Django Project :
```
django-admin startproject djangogirl .
```

#### Verify the Project Structure :
You should see files like manage.py, djangogirl/settings.py, etc.

#### Run Migrations :
Apply initial migrations to set up the database:
```
python manage.py migrate
```

#### Start the Development Server :
python manage.py runserver