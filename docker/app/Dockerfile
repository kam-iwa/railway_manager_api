FROM python:3.11-slim-bookworm

ENV PYTHONDONTWRITEBYTECODE=1

COPY requirements.txt /app/
WORKDIR /app

RUN pip install --no-cache-dir -r ./requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]