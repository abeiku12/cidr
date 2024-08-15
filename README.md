[![Build](https://github.com/prabhatraghav/cidr/actions/workflows/main.yml/badge.svg)](https://github.com/prabhatraghav/cidr/actions/workflows/main.yml)
[![pages-build-deployment](https://github.com/prabhatraghav/cidr/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/prabhatraghav/cidr/actions/workflows/pages/pages-build-deployment)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fcidr.prabhatraghav.online%2F)

**CIDR Range Visualizer**
**An Interactive Web-based IP Address Range Display App**

[![cidr.png](cidr.png)]()

## Dev

Install dependencies and run the development server:

```bash
$ yarn
$ yarn run start
```

## Build

Manually building the static content into the `dist/` directory can be done with:

```bash
$ yarn run build
```

## Docker

You can build a Docker Image from an included Dockerfile and run it as a container:

```bash
docker build -t cidr.xyz:0.1 .
docker run -d --rm -p 80:80 cidr.xyz:0.1
```

## Deployment

Deployment is automated from `master` branch via Netlify
