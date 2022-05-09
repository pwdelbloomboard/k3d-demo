# Demo k8s Configuration Yaml

This is a demo k8s configuration yaml which can be used with, "kubectl apply" to quickly spin up an application.

The deployment container image is under:

k8s/deployment.yaml > 

```
    spec:
      containers:
      - name: devops-toolkit
        image: ghcr.io/pwdelbloomboard/ps-container
```