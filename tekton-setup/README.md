# Instructions

```
# Set contexts to correct namespace

# TODO script injection from Bitwarden
kubectl create secret generic regcred --from-file=.dockerconfigjson=$HOME/.docker/config.json --type=kubernetes.io/dockerconfigjson

#TODO use ytt to add from .ssh at
k apply tekton-setup/github.yml

k apply tekton-setup/service_account.yml

```