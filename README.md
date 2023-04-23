<!-- FLASK_APP=root_file_name
FLASK_ENV=env_mode
FLASK_DEBUG=debug_mode
The following command is required for project to up and running-
docker-compose up -d -->
<!-- # docker build -t flask-rest-api .
# docker run -p 5000:5000 flask-rest-api
# docker run -dp 5005:5000 -w /app -v "$(pwd):/app" flask-rest-api -->

Add .flaskenv file add the following

> FLASK_APP=app.py
> FLASK_ENV=development
> FLASK_DEBUG=True

Use below command for up and running...

> docker-compose up -d
