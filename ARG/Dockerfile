FROM almalinux:9
ENV Course="Devops" \
    duration="120hr"
ARG ${username:-some_user}
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD [ "sleep", "100" ]