# coding-project-template

## Exercise 3

Sometimes after runing the command below there is a warning, no pods are created, and/or there is a ConfigError.

```
kubectl apply -f deployment.yaml
```

This repo has updated Dockerfile and the two Deployment files to fix this issue by specyfing user and adding security context.
