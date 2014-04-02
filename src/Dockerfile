FROM tianon/centos:6.5
RUN yum install -y https://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
RUN yum install -y python-pip
RUN pip install flask
ADD . /app
WORKDIR /app
EXPOSE 5000
CMD python app.py
