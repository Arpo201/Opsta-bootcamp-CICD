FROM python:3.7.7-slim

WORKDIR /usr/src/app/

COPY /src .

RUN pip install -r requirements.txt

EXPOSE 9080
CMD ["python", "productpage.py", "9080"]