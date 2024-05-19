FROM python:3-slim
WORKDIR /programas/api-user
RUN pip3 install flask flask-cors mysql-connector-python
COPY . .
RUN python3 db.py
CMD [ "python3", "./app.py" ]
