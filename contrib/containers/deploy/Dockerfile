FROM phusion/baseimage:focal-1.0.0
LABEL maintainer="Gymnasium Developers <dev@gymnasium.org>"
LABEL description="Dockerised Gymnasium, built from Travis"

ARG USER_ID
ARG GROUP_ID

ENV HOME /home/gymnasium

# add user with specified (or default) user/group ids
ENV USER_ID ${USER_ID:-1000}
ENV GROUP_ID ${GROUP_ID:-1000}
RUN groupadd -g ${GROUP_ID} gymnasium && \
    useradd -u ${USER_ID} -g gymnasium -s /bin/bash -m -d /home/gymnasium gymnasium && \
    mkdir /home/gymnasium/.gymnasium && \
    chown ${USER_ID}:${GROUP_ID} -R /home/gymnasium

COPY bin/* /usr/local/bin/

RUN chmod a+x /usr/local/bin/*

USER gymnasium

VOLUME ["/home/gymnasium"]

EXPOSE 17217 9999 27217 27218

WORKDIR /home/gymnasium
