FROM python:3.9
WORKDIR /app

COPY ./requirements.txt .
RUN pip3 install 'git+https://github.com/AdamStrojek/libetrv.git' -r ./requirements.txt
COPY ./run.sh .
RUN chmod +x run.sh

CMD ["/app/run.sh"]
