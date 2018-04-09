# pm2-tsc-openshift

This repository contains **non-root** Node.js docker image with [PM2](http://pm2.keymetrics.io/) and TypeScript based on [RHEL](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux).

## How to use this Docker image

### Install

Install the image:

```
docker pull dapowerplay/node-pm2-tsc
```

Alternatively, pull a specific version:

```
docker pull dapowerplay/node-pm2-tsc:0.1.0
```

### Usage

Start container:

```
docker run -d dapowerplay/node-pm2-tsc:0.1.0
``````

### Info

Image is s2i enabled and OpenShift ready
