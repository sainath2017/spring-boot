Docker
=========

> docker build -f[file] Dockerfile(Docker file name default) -t[targetName] docker-name-of-image
> docker build -f Dockerfile -t docker-spring-boot .  // Current directory resides the application
> docker images (to get all images)
> docker run -p[push] 8085(target port):8085(configured) docker-spring-boot[Image name]
