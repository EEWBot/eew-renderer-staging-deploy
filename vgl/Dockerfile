FROM ghcr.io/eewbot/eew-renderer:master@sha256:7c7d55706674144258abcf479861e203528f336986f56e5a8735174d3826f530

ARG VIRTUALGL_VERSION
ADD https://github.com/VirtualGL/virtualgl/releases/download/${VIRTUALGL_VERSION}/virtualgl_${VIRTUALGL_VERSION}_amd64.deb \
    virtualgl_${VIRTUALGL_VERSION}_amd64.deb

RUN apt-get install -y /virtualgl_${VIRTUALGL_VERSION}_amd64.deb
