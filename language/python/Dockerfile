FROM python:3.12

WORKDIR /app/language/python
COPY language/python/ .

RUN pip install -r requirements.txt

CMD ["gunicorn", "--bind", "0.0.0.0:8000", "app:app"]
