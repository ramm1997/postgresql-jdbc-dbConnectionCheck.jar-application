FROM python:3.6-alpine
RUN apk add --update bash
RUN apk add --update curl
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]

