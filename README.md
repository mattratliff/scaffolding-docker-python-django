Python-Django Scaffolding Template

How to Run:

- Build the contiainer:  "docker-compose build"
- Start the containers: "docker-compose up -d"
- Create the model (log into the web container)
>>> docker-compose exec web bash
>>> python manage.py migrate

Note on Migrations:
In order to create new tables you must create a new model in models.py and run makemigrations and then migrate
