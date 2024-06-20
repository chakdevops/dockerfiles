ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "version: ${version}, course: ${COURSE}, trainer: ${TRAINER}"
ENV COURSE=${COURSE}
ENV TRINER=${TRAINER}
CMD ["sleep", "100" ]