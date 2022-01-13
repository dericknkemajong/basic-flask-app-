FROM python:3.7
WORKDIR /usr/local/bin/python -m 
COPY . .
RUN pip install --upgrade pip
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["./app.py"]
