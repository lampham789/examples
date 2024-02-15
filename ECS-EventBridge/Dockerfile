FROM python:latest

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENV PORT 8000

EXPOSE $PORT

CMD [ "python", "app.py" ]

# CMD [ "python", "script.py" ]