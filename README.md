# PGQueryPlans

## Installation

### 1. Activate virtual environments
To create a virtual environment within this new directory, use the format:

```
$ python3 -m venv <name_of_env>
``` 

A common choice is to call it .venv, as we do here.
```
$ python3 -m venv .venv
```


Once created, a virtual environment must be activated.  
```
$ source .venv/bin/activate
(.venv) $
```


To deactivate and leave a virtual environment, type deactivate.
```
(.venv) $ deactivate
$
```

### 2. Install requirements
```
pip install -r requirements.txt
```

### 3. Run the development server
```
(.venv) $ python3 manage.py runserver

Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until
you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
April 13, 2023 - 13:15:03
Django version 4.2, using settings 'django_project.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-BREAK.
```

![image](https://github.com/ratdbs/dbenchvis-back/assets/135293038/f4b8d8fd-5fc7-4235-97c7-dc2cc514d2ac)

<!-- ### PyPI (Python Package Index)
```
$ python -m pip install --upgrade pip
```
### Install Django
```
$ source .venv/bin/activate
(.venv) $ python3 -m pip install django~=4.2.0
```

### Django Project
To create a new Django project, use the command:
```
(.venv) $ django-admin startproject <project_name>
```

By default Django will create this directory structure:
```
django_project/
    ├── django_project
    │   ├── __init__.py
    │   ├── asgi.py
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── manage.py
    └── .venv/
``` -->
