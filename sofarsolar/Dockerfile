FROM python:3.10

ADD inverter /inverter
ADD run.sh /

RUN pip install paho-mqtt anyconfig \
    && chmod +x /run.sh

CMD [ "/run.sh" ]
