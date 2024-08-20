FROM python:3.11-alpine 
# FROM  python:3.11-slim-budocker build -t rand-quoute:1.0 .llseye

WORKDIR /usr/src/app

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

# app will run on port 3000
EXPOSE 3000

CMD [ "python", "./app.py" ]
