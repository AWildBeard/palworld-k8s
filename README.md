## K8s yaml for Palworld
`grep` for CHANGEME to find things *you* need to change

`kubectl apply -k .` in the root of the repo to deploy to your default namespace. You must have a loadbalancer capability in the cluster as this relies upon that. You also need persistent storage.
