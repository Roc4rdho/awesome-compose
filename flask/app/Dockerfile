FROM python:3.7-alpine 
WORKDIR /app 
RUN pip3 install -r requirements.txt 
COPY . /app 
ENTRYPOINT ["python3"] 
CMD ["app.py"]
