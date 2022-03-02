# Django Set Up
<br />

## Install pip
<br />

You'll need to make sure you havce the lastest version of pip installed
```
py -m pip install --upgrade pip
```
## Install Virtual Environment
<br />

```
py -m pip install --user virtualenv
```
## Create Virtual Environment
<br />

```
py -m venv env
```
## Activate Virtual Environment
<br />

After your virtual environment has been created, run this command:
```
.\env\Scripts\activate
```

As long as your virtual environment is activated, pip will install packages into that specific environment 

## Required Module
<br />
 
To install required modules for django, run this **INSIDE** of the virtual environment:
```
pip install -r requirements.txt
```

##  Get settings.py
<br />

Open discord server and copy the settings.py file into the project file 

## Connect Database
<br />

Enter database credentials and refer to DATABASES dictionary in settings.py and set up your connection to postgres

[Django database connection documentations](https://docs.djangoproject.com/en/4.0/ref/settings/#databases)


## Finish Setting Up Django
<br />

After the connection is made, run the following commands to migrate and run server:
```
python manage.py migrate
python manage.py runserver
```

Once you run the server, a similar prompt should appear in the terminal



```

System check identified no issues (0 silenced).<br>
March 02, 2022 - 00:05:24<br>
Django version 4.0.3, using settings 'ctrlIntell_project.settings'<br>
Starting development server at http://127.0.0.1:8000/<br>
Quit the server with CTRL-BREAK.

```
Now open up your web browser and go to the address

```
localhost:8000
```

