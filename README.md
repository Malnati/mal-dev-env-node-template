# Custom development env NodeJs template

A repository containing an application and Dockerfile to use of Docker as Custom development env NodeJs template in a container image.

You can build and run the image with the following command:

```shell
docker build -t mal-dev-env-node-template:v1 .
docker run mal-dev-env-node-template:v1
```

The application consists of a basic ExpressJS server and uses an intentionally old version of Express and Alpine base image.
 
