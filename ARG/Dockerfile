FROM almalinux:9
ENV course="DevOps"\
    trainer="Raghu"
## Here below username is key and someuser is default value
ARG ${username:-someuser}
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD ["sleep", "100"]
