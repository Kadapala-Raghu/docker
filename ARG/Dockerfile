ARG version
FROM almalinux:${version}:-9
ENV course="DevOps"\
    trainer="Raghu"
## Here below username is key and someuser is default value
ARG USERNAME=RaghuKadapala
RUN echo "Hello ${USERNAME}}"
CMD ["sleep", "100"]


# $ docker build -t arg:1.0 --progress=plain --no-cache

# If you want to override the ARG value
# $ docker build -t arg:1.0 --progress=plain --no-cache --build-arg USERNAME=KadapalaRaghu

# While checking in env in container, there would be no saving ARG values and not accessble and it access at image building
    #It cannot be useful after FROM instructions


# # FAQ -> i want to use ARG after FROM, how can We 
# FAQ > ARG value ni container lopala use cheyyali ante 
# /*
# ARG version
# FROM almalinux:${version}:-9
# ENV course="DevOps"\
#     trainer="Raghu"
# ## Here below username is key and someuser is default value
# ARG USERNAME=RaghuKadapala
# ENV USERNAME=$USERNAME
# RUN echo "Hello ${USERNAME}}"
# CMD ["sleep", "100"]


# */
# # Feb-26 Session 44 at 50:00 Minutes