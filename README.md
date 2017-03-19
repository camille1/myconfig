# myconfig

## Jupyter Notebook
* Managing env `conda info --envs`
* remove env `conda remove --name name_of_kernel --all`
* Activate en `activate name`
* Install a new env and register env in ipykernel `conda create -n tensorflow python=3.5 ipykernel`

## Django

### Installation
* `pip install virtualenvwrapper-win`
* `mkvirtualenv myproject`
* `workon myproject`
* `pip install django`
* `django-admin --version`

### Création d'un projet
* `django-admin startproject mysite`

### Serveur de développement
* `python manage.py runserver`

### Création d'application
* `python manage.py startapp polls`
* `python manage.py runserver`

### Migration
if Models (SQL), make migration
* `python manage.py makemigration`
* `python manage.py migrate`

### Admin
* `python manage.py createsuperuser`
