FROM ubuntu
RUN apt-get update && apt-get install -y curl
ADD app /app
ENTRYPOINT bash /app/feed
