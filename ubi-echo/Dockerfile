FROM registry.access.redhat.com/ubi8/ubi:8.0
COPY . /home/
RUN chmod -R 777 /home/
USER 1001
CMD bash -c "while true; do echo test; sleep 5; done"
