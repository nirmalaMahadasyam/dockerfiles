ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE=PHP
ARG  TRAINER=SIVA
ARG Duration="120hrs"
ENV Duration = ${Duration}
RUN echo "Couse is: ${COURSE}, and the Trainer is: ${TRAINER}, and Duration: ${Duration}"
CMD ["sleep","100"]
