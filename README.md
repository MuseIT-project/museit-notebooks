#MuseIT Jupyter Notebooks collection

Warning: you need [Docker Desktop](https://www.docker.com/products/docker-desktop/) or Docker.io installed in your OS.

Copy configuration files and change password or token:
```
cp .env-sample.py .env
cp config-sample.py config.py
```
Now you can start notebook by running:
```
docker-compose up -d
```
Open Jupyter Notebook on http://0.0.0.0:8888 and enter your password or token from .env file.
