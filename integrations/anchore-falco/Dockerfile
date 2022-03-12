FROM python:3.7.11-stretch

RUN pip install pipenv

WORKDIR /app

ADD Pipfile /app/Pipfile
ADD Pipfile.lock /app/Pipfile.lock
RUN pipenv install --system --deploy

ADD . /app

CMD ["python", "main.py"]
