### Project setup

#### Note: Dependencies/ Prequisites

- [poetry](https://python-poetry.org)

1. ##### Clone the repo

```bash
git clone https://gitlab.com/nsjayanth/django-3-boilerplate-project.git <proeject-name>
```

ex:

```bash
git clone https://gitlab.com/nsjayanth/django-3-boilerplate-project.git django_3_boilerplate
```

2. go to the project

```bash
cd django_3_boilerplate
```

3. Install the requirements

   - Using `poetry` (environement will be created with the name `.venv`)
     Install requirements

     ```bash
     poetry install
     ```

     Activate the environment

     ```bash
     poetry shell
     ```

   - Using `pip`
     create a virtual environment manually
     ```bash
     python3 -m venv .venv
     ```
     Activate the environment manually
     ```bash
     source .venv/bin/activate
     ```
     Install requirements
     ```bash
     pip install -r requirements
     ```

4. Running migrations (only first time)

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

5. Finally to run the server locally

```bash
python manage.py rrunserver
```
