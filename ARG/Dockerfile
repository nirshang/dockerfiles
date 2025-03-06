ARG version
FROM almalinux:${version:-9}
ENV Course="Devops" \
    duration="120hr"
ARG NAME=Latha
RUN echo "Hello user: ${NAME}, image version: ${version}" > /tmp/version.txt
CMD [ "sleep", "100" ]