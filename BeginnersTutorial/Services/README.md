### Beginners Tutorial

**disclaimer** my interpretation about what i learned..

## Instructions


- create a namespace:

`kubectl create namespace my-frontend-namespace`

- deploy the app:

`kubectl apply -f .`

- Forward the port of your app so that it can be accessed from outside your cluster machine:

`kubectl port-forward service/app1-service 8080:80 --address 0.0.0.0 -n my-frontend-namespace`

You can scale your app if you want. :)

### Test

`curl x.x.x.x:8080`