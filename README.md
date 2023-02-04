# Jenkins Project

## Main Points :
-----------------------------------------------------------------
* Infrastructure : 1 VPC | 1 Subnet | 1 Enternet-Gateway | Ec2 instance on Subnet
* Deploy Jenkins in minikube as a pod (Master) on ec2 instance
* Doploy slave as a pod on minikube to run jobs on it
* install nginx and change configration to work as (reverse proxy) to can hit pods
* make pipeline multi-branche listen from private GitHub repo have branches(main|dev|release)
* Dockerfile to can build the app on image
* build and push images on private DockerHub repo at release branche
* deploy the latest image pushed on dockerHub repo on pod

## ScreenShots :
-----------------------------------------------------------------
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/1.png)
-----------------------------------------------------------------  
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/2.png)
-----------------------------------------------------------------
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/3.png)
-----------------------------------------------------------------
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/4.png)
-----------------------------------------------------------------
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/5.png)
-----------------------------------------------------------------
![agent](https://github.com/Badawi02/jenkins-Project/blob/main/images/6.png)
-----------------------------------------------------------------
## Contributors:
- [Ahmed Badawi](https://github.com/Badawi02)
