# K8s-images
Kubernetes images 
Now Kubernetes Cluster deployed with container,but pull K8S docker images nearly is impossible because of the GFW，So we need seek for another way，we build k8s image with dockerfile on Dockerhub that located in the overseas，then we pull k8s docker images from docker.hub.
This project provide the dockerfile used by Dockerhub when build k8s images.

How do use this dockerfile?
1、you need a Dockerhub account
2、you need create docker registry on dockerhub
3、associate you dockerhub registory with this github project
4、build docker image on dockerhub


the dockerhub repository please reference https://hub.docker.com/r/warrior
