
# Fast API Learning

Building My First API with Python's Fastest API Web Framework!

### Agenda

Building an API using:

- FastAPI with Uvicorn(Get and Post Data)
- SQLAlchemy + Alembic (for migrating database)
- PostgreSQL + PGAdmin
- Docket/Docker-Compose
- Configuring Environment Variables


### Tutorial

pip install fastapi fastapi-sqlalchemy pydantic alembic psycopg2 uvicorn python-dotenv

docker-compose run app alembic revision --autogenerate -m "New Migration"  
docker-compose run app alembic upgrade head

docker-compose build  
docker-compose up