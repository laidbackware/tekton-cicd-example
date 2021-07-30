# Instructions

```
k apply service_account.yml

k create secret docker-registry srd-docker-registry  --docker-server=docker.io  --docker-username=abcd  --docker-password=efgh  --docker-email=ijkl -n tekton-pipelines

k create secret docker-registry srd-docker-registry --docker-server=docker.io --docker-username=abcd --docker-password=efgh --docker-email=ijkl -n java-maven-demo

# Temporarily update github.yml to add private key
k apply service_account.yml
# Remove public key from github.yml


```