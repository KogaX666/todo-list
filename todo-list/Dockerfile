FROM python:3.11.2-alpine

WORKDIR /todo-list

COPY requirements.txt ./
COPY app.py ./
COPY static ./
COPY templates ./

RUN pip install -r requirements.txt

CMD [ "python", "app.py" ]
EXPOSE 5000