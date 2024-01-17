FROM python:3.8-slim

RUN apt-get update && apt-get install -y ssh-client

RUN pip install ansible

WORKDIR /ansible

CMD [ "ansible-playbook", "--version" ]
