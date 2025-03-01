FROM python:3.9
WORKDIR /app
COPY . .
RUN pip install --upgrade pip
RUN pip install thriftpy2==0.4.16
# Install packages directly instead of from requirements.txt
RUN pip install redis==2.10.6 py_zipkin==0.20.2 requests
CMD ["python", "main.py"]
