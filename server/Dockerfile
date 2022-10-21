FROM python:3.9.14-slim-buster

WORKDIR /usr/src/app
# It's only a single file.  It has to be in the same directory as the
# Dockerfile, or a subdirectory, but not a parent or sibling.
COPY requirements.txt .
RUN apt-get update 
RUN pip install -r requirements.txt
COPY server.py .
COPY utils.py .
COPY templates/ templates/
COPY static/ static/
COPY artifacts/ artifacts/
EXPOSE 5000
CMD ["python", "server.py"]