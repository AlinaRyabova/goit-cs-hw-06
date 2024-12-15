FROM python:3.13-slim

WORKDIR /webapplication

COPY . /webapplication

RUN pip install --no-cache-dir -r /webapplication/requirements.txt

EXPOSE 3000
EXPOSE 6000

CMD ["python", "main.py"]