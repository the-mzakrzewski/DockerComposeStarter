FROM python:3.13-alpine

WORKDIR /usr/src/app

COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir --upgrade -r requirements.txt

CMD ["fastapi", "dev", "main.py", "--host",  "0.0.0.0"]