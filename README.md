# template_accounts

### Rename app
Use command from file new_app.command


## Project setup
### Setup virtual env and pip.
```
$ virtualenv grkrcn-env
```
### Activate virtual env
Linux
```
$ source grkrcn-env/bin/activate
```
Windows
```
> grkrcn-env\bin\activate
```
### Download packages
```
$ pip install -r requirements.txt
```
### .env
Create .env file or rename .env.local to .env

### Do migration
```
$ python manage.py migrate
```
### Run server
```
$ python manage.py runserver
```


## Docker launch
### Build image
```
docker-compose up --build
```

### Creating \admin\ superuser
```
docker compose exec server python manage.py createsuperuser
```
