steps which followed
Followed the steps

1 - python,git, docker and minikube already setup in my test server
2 - wrote the python program
3 - wrote the Dockerfile and specified the instruction inside the Dockerfile
4 - ran the docker build command to create the image and pushed to dockerhub with latest tag for time being as in organization we have nexus/jfrog artifact
5 - tested in server if the docker container is working with specified application by using docker run <image name>
6 - created the deployment.yaml file to run this using the minikube command like "kubectl apply -f deployment.yaml"
7 - if we need to expose to public then we can do it by using "kubectl expose deployment <name> --type=LoadBalancer --port=<port>"
