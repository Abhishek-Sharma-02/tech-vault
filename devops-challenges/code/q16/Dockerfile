FROM python:3.14.3-slim

WORKDIR /app

ADD requirements.txt .

RUN pip install -no-cache-dir -r requirements.txt

ADD . .

CMD ["python", "app.py"]
