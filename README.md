
python -m venv env
```


env\Scripts\activate


pip install -r requirements.txt
```

> **Note:** If you're using newer versions of python(3.10+), you may need to add the `--use-deprecated=legacy-resolver` option when installing dependencies with `pip` to avoid errors :

pip install -r requirements.txt --use-deprecated=legacy-resolver
```python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser

python manage.py runserver
```

Now the project should be running on http://127.0.0.1:8000/

Login as admin and add some courses, teacher and students



