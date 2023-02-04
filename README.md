# Jenkins Project

* Infrastructure : 1 VPC | 1 Subnet | 1 Enternet-Gateway | Ec2 instance on Subnet
* Deploy Jenkins in minikube as a pod on ec2 instance
* install nginx and change configration to work as (reverse proxy) to can hit pods
* make pipeline multi-branche listen from private GitHub repo have branches(main|dev|release)
* Dockerfile to can build the app on image
* build and push images on private DockerHub repo at release branche
* deploy the latest image pushed on dockerHub repo on pod

![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/1.jpg)
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/2.jpg)
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/3.jpg)
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/4.jpg)
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/5.jpg)
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/6.jpg)