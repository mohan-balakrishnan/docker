steps to push docker image to docker hub

1. docker login 
<enter your docker hub username & password>

2. To tag
    syntax: docker tag <tagname>:latest <DockerHubUserName>/<RepoName>:latest

    eg: docker tag mywebapp:latest username/mydemoapp:latest

3. push docker image 
    docker push username/mydemoapp:latest
