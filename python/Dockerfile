FROM alpine:3.4

ENV FLASK_APP /app/hello.py
RUN apk add --update python py-pip && \
		pip install flask
ADD hello.py /app/hello.py
EXPOSE 5000

CMD python -m flask run --host=0.0.0.0 
