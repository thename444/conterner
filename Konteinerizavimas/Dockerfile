FROM python:3.13.0

WORKDIR /app

COPY requirements.txt . 
COPY /app .

RUN pip install -r requirements.txt

CMD ["python", "main.py"]