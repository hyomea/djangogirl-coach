# djangogirl-coach guide 2025 Grand Rapids

## Set Up a GitHub Repository if starting from github codespaces
1. Create a New Repository:
   - Go to [GitHub](https://github.com) and create a new repository.
   - Pick a name.
   - Optionally, add a README file, `.gitignore` (choose Python for Django), and a license.

2. Enable GitHub Codespaces:
   - Navigate to the repository page.
   - Click the **Code** button and select **Codespaces > Create codespace on main**.
   - This will launch a new Codespace for your repository.

Note: if starting from local machine, follow the instructions below to set up a local environment.
https://tutorial.djangogirls.org/en/deploy/ 


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
```
python manage.py runserver
```

#### Commit and Push Changes
1. Stage Changes :
Add all changes to Git:
```
git add .
```
2. Commit Changes :
Commit the changes with a message:
```
git commit -m "Initial project setup"
```
3. Push to GitHub :
Push the changes to your repository:
```
git push origin main
```

#### Walk through the turorial: 
https://tutorial.djangogirls.org/en/django_models/

