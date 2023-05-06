# Build and run:
#   docker build -t bc:7.6 -f Dockerfile .
#   docker run -d --name bc76 bc:7.6
#
# stop:
#   docker stop bc76
#

FROM scratch
ADD bclinux-7.6-docker.tar.xz /

LABEL org.label-schema.schema-version="1.0" \
    org.label-schema.name="BCLinux Base Image" \
    org.label-schema.vendor="BCLinux" \
    org.label-schema.license="GPLv2" \
    org.label-schema.build-date="20230505"

CMD ["/bin/bash"]

