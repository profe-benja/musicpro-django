# Noticias django

## Instalación
```
git clone https://github.com/profe-benja/noticias-django

python -m venv myvenv

.\myvenv\Scripts\activate

cd noticias-django

pip install -r requerimientos.txt

```

## Migraciones
elimina el db.sqlite3
```
python manage.py makemigrations
python manage.py migrate
```

## RUN
Servidor normal
```
python manage.py runserver
```


Servidor en red lan
```
ipconfig
python manage.py runserver 0.0.0.0:5000
```
