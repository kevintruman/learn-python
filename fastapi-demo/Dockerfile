FROM python:3.11.8-alpine3.19

WORKDIR /app

COPY . .
RUN pip install -r requirements.txt

CMD ["uvicorn", "main:app", "--host=0.0.0.0", "--port=8000"]
#CMD ["python", "main.py"]
