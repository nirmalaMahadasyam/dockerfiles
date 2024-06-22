ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE=PHP
ARG  TRAINER=SIVA
RUN echo "Couse is: ${COURSE}, and the Trainer is: ${TRAINER}"
CMD ["sleep","100"]
