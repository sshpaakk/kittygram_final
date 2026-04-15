FROM python:3.9-slim

WORKDIR /app

<<<<<<< HEAD
=======
RUN pip install --upgrade pip

>>>>>>> f559300 (Configure Kittygram Docker and CI/CD)
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

<<<<<<< HEAD
RUN python manage.py collectstatic --noinput

CMD ["gunicorn", "kittygram_backend.wsgi:application", "--bind", "0:8000"]
=======
CMD ["gunicorn", "kittygram_backend.wsgi:application", "--bind", "0.0.0.0:8000"]
>>>>>>> f559300 (Configure Kittygram Docker and CI/CD)
