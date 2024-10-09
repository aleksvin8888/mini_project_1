
FROM python:3.9-slim

RUN apt-get update && apt-get install -y \
    libpq-dev gcc

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . /app

WORKDIR /app

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]