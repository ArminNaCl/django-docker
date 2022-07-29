FROM python:3.10.5

WORKDIR /opt/backend

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFY 1

RUN pip install --upgrade pip
COPY ./requirements.txt /opt/backend/requirements.txt
RUN chmod +x /opt/backend/requirements.txt
RUN pip install -r requirements.txt

COPY . /opt/backend/