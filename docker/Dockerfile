FROM python:3.4-alpine
ADD . /code
WORKDIR /code
RUN pip install -r ./src/requirements.txt
ENTRYPOINT ["python", "./src/app.py"]