# tekton-cicd-example

```
kubectl create -f tasks/

tkn task start git-clone --param url=https://github.com/tekton-example/java-app-example.git --param revision=main --param subdirectory=application-source --workspace name=output,claimName=pipeline-pvc --showlog
```