# openbar-main-backend
Main backend for the OpenBar project

```
python -m venv venv
source venv/bin/activate
pip install -r requirements-dev.txt
```

```
### Setup two databases
docker-compose up -d

### Alembic migrations upgrade and initial_data.py script
bash init.sh
```

```
uvicorn app.main:app --reload
```