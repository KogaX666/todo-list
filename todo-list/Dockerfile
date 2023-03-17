FROM python:3.11.2-alpine

WORKDIR /todo-list

COPY requirements.txt ./
COPY app.py ./
COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000
CMD [ "python", "app.py" ]