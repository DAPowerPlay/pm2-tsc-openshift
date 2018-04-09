FROM registry.access.redhat.com/rhscl/nodejs-8-rhel7:1-11
MAINTAINER DPP <contact@dapowerplay.com>

USER 1001
RUN bash -c "npm install pm2 -g" && \
bash -c "pm2 install typescript" && \
fix-permissions /opt/app-root