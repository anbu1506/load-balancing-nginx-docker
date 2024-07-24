FROM python:latest

RUN  mkdir -p /html  

ADD index.html /html

CMD ["/bin/python3","-m", "http.server","8001","--directory","/html"] 