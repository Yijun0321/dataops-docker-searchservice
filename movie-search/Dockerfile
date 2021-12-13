FROM python:3.9.9
ADD app /app
RUN pip install flask elasticsearch
EXPOSE 8000
ENTRYPOINT python /app/server.py
