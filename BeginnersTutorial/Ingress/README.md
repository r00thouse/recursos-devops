`kubectl create namespace my-frontend-namespace`

`kubectl apply -f .`

`curl http://${MINIKUBE_IP}:80/ -H "Host: app1.example.com"`