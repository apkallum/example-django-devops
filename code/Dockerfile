FROM python:3.7.4
ENV PYTHONUNBUFFERED 1
# Something wrong with COPY
ADD ./banana /opt/banana 
ADD manage.py /opt/

WORKDIR /opt/
RUN pip3 install -r /opt/banana/requirements.txt