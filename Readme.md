# Command
minikube start --driver=docker

docker tag project1_client komalreddyk/firstrepo

docker push komalreddyk/firstrepo

kubectl create deployment kubercount --image=komalreddyk/firstrepo

kubectl expose pod kubercount-5ff776df8c-mg2d --port=3000 --type=NodePOrt --name=kuber-service2

minikube service kuber-service2

![Alt text](image.png) 

# Result

![Alt text](image-1.png)
