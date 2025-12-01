FROM python:3.11-slim

COPY . /requests
WORKDIR /requests

RUN pip install -r requirements.txt

CMD ["python3", "requests_script.py"]

# docker build . --tag requests:0
# docker run requests:0