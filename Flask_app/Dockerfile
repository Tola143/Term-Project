FROM alpine:latest
#RUN apk add --no-cache python3-dev \
#    && pip install --upgrade pip
WORKDIR /Flask_app
COPY . /Flask_app
#RUN pip --no-cache-dir install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["app.py"]