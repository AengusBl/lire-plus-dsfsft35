FROM python:3.12

WORKDIR /app

COPY . /app/

RUN pip -U
RUN pip install -r requirements.txt

CMD ["python3", "/app/app.py"]