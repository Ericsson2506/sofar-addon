FROM python:3.10

ADD inverter /inverter
ADD run.sh /

RUN pip install paho-mqtt anyconfig

CMD [ "chmod 777 run.sh" ]

CMD [ "/run.sh" ]
