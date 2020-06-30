Hi, Steps to do this project
STEPS
1. CREATE PORTFOLIO FOLDER
2. CREATE VIRTUAL ENVIRONMENT
COMMAND : python -m venv pvenv
3. ACTIVATE VIRTUAL ENVIRONMENT
COMMAND : source pvenv/bin/activate
4. INSTALL DJANGO
COMMAND : pip install Django
5. CREATE PROJECT
COMMAND : Djangoadmin startproject mywebproject .
6. RUNSERVER
COMMAD : python manage.py runserver
7. CREATE STATIC ROOT 
CODE : STATIC_ROOT = os.path.join(BASE_DIR,'static')
8. RUN MIGRATIONS
COMMAND: python manage.py migrate 
9. CREATE SUPERUSER - ADMIN
COMMAND: python manage.py createsuperuser
10. CREATE projects app
COMMAND: python manage.py startapp projects
11. REGISTER APP ON SETTINGS.PY
add 'projects' to Installed Apps