FROM ubuntu:16.04
MAINTAINER Boris Kolganov <b.kolganov@corp.mail.ru>

RUN apt-get install -y python python-pip && pip install numpy scipy keras tensorflow

ENV SOLUTION_CODE_ENTRYPOINT=main.py
ENV SOLUTION_CODE_PATH=/opt/client/solution
ENV RUN_COMMAND='python -u $SOLUTION_CODE_PATH/$SOLUTION_CODE_ENTRYPOINT'
