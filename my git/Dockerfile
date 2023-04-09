FROM python:3.9
WORKDIR /flaskex-master 
COPY requirements.txt /flaskex-master
RUN pip3 install --upgrade pip -r requirements.txt
COPY . /flaskex-master
EXPOSE 5000