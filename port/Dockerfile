FROM python:3.9

WORKDIR /port

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY port.py .

CMD ["python", "port.py"]