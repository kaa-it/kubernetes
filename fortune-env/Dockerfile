FROM ubuntu:latest
RUN apt update ; apt -y install fortune
ADD fortuneloop.sh /bin/fortuneloop.sh
RUN chmod 777 /bin/fortuneloop.sh
ENV INTERVAL=10
ENTRYPOINT ["/bin/fortuneloop.sh"]