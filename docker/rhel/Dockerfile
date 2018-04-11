FROM registry.access.redhat.com/rhscl/nodejs-8-rhel7:1-11
MAINTAINER DPP <contact@dapowerplay.com>

ARG NPMRC_CUSTOM
USER 1001
RUN bash -c "npm install pm2 -g" && \
bash -c "pm2 install typescript" && \
fix-permissions /opt/app-root
RUN echo $NPMRC_CUSTOM > ~/.npmrc