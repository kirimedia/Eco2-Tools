FROM python:3.9
WORKDIR /app

RUN pip3 install 'git+https://github.com/AdamStrojek/libetrv.git'
COPY ./run.sh .
RUN chmod +x run.sh

CMD ["/app/run.sh"]
