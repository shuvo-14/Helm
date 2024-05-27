`helm create api-server`

`helm package api-server/`

//for reuse

`helm install test ./api-server/`

`kubectl port-forward svc/test-service 3201:3200`

`http://localhost:3201/`