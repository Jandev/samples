FROM python:3.7.1-alpine3.8
WORKDIR /app
COPY .dockerfiles . 
RUN pip install requests
ENTRYPOINT ["python"]
CMD ["app.py"]
