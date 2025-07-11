FROM python:3.13.5-slim

WORKDIR /app
COPY . ./

RUN pip install requests requests_oauthlib

ENTRYPOINT ["python", "/app/builder.py"]