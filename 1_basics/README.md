# Docker Basics Tutorial

Watch the tutorial: https://www.youtube.com/watch?v=gSdm1ghBYJ4

To run the build locally, install docker on your machine and then run

```
docker build -t step1 .
docker run -v `pwd`:`pwd` -w `pwd` step1 node hello-world.js
```

Alternatively to providing the command line arguments, you can also specify that in your Dockerfile.
I've done so in Dockerfile2. Like this, the instructions simplify to:
```
docker build -t step1-alternative -f Dockerfile2 .
docker run step1-alternative
```
