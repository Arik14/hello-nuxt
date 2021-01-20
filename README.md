# hello-nuxt

## Run in Docker
1. Build docker image
2. Run docker image in container
3. Nuxt app can be seen in http://172.17.0.2:4000/ or http://localhost:4000

### Available CLI syntax
```bash
# Build docker image
$ docker build -t image-name .

# View list of existing docker images
$ docker images

# Delete docker image
$ docker rmi image-name

# Run docker image in a container (with console active)
$ docker run --name container-name -p 4000:4000 image-name

# Stop active container
$ docker stop container-name

# Delete container
$ docker rm container-name

```
Dockerfile is created using Reference From https://jonathanmh.com/deploying-a-nuxt-js-app-with-docker/


## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
