FROM python:3.7.5-alpine

WORKDIR /app

EXPOSE 5000

COPY .  .

RUN pip install -r requirements.txt 

CMD ["python3", "run.py"]
