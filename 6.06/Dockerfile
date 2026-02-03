FROM scratch

ARG TARGETARCH
ADD ubuntu-6.06-${TARGETARCH}.tar.xz /
COPY sources.list /etc/apt/sources.list

LABEL org.opencontainers.image.title="Ubuntu"
LABEL org.opencontainers.image.version="6.06"
LABEL org.opencontainers.image.ref.name="ubuntu"

ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin

CMD ["/bin/bash"]
