for initial setup in python Due to the removal of the long-deprecated pkgutil.ImpImporter class, the pip command may not
 work for Python 3.12. You just have to manually install pip for Python 3.12

"python -m ensurepip --upgrade"
"python -m pip install --upgrade setuptools"

be sure that django has been installed as per the requirement.txt as of 06/07/2024
django 5.1.a.1

$ django-admin startproject core .  #Create Project
$ python manage.py startapp main    #Start App

initialize the django instance to sql lite (postgres will be used in later version)

python manage.py migrate
python manage.py startapp main