FROM python:3.9 

WORKDIR /code 

COPY . /code  

RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt

CMD ["uvicorn", "restful_server:app", "--host", "0.0.0.0", "--port", "8080"]

