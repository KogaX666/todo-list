FROM python:3.11.2-alpine

WORKDIR /todo-list

COPY requirements.txt ./
COPY todo-list ./

RUN pip install -r requirements.txt

CMD [ "python", "app.py" ]
EXPOSE 5000