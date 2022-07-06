# PyNode (Python + Node.js)

Docker image containing Python (v3.9.9) and Node.js (v14.17.6) for full-stack application development.

## Pushing to Docker Hub

### `latest` tag

- Change into the `bullseye` directory.
- Run `docker build -t landedhomes/pynode:latest .` to build the image.
- Run `docker push landedhomes/pynode:latest` to update the tagged image on Docker Hub.

### `development` tag

- Change into the `development` directory.
- Run `docker build -t landedhomes/pynode:development .` to build the image.
- Run `docker push landedhomes/pynode:development` to update the tagged image on Docker Hub.
