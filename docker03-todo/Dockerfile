FROM python

RUN mkdir /app
WORKDIR /app
add . .

RUN pip install -r requirements.txt

ENTRYPOINT FLASK_APP=/app/todo.py flask run --host=0.0.0.0

