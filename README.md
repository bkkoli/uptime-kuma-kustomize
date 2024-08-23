# uptime kuma kustomize
Create Workloads of uptime kuma with kustomize in k8s.

## source codes of uptime-kuma in github
https://github.com/louislam/uptime-kuma

## docker image of uptime-kuma in docker hub
https://hub.docker.com/r/louislam/uptime-kuma

## How to use

- base
```bash
kubectl apply -f ./base
```
- customize for env
> Please refer an examples located in "./overlays/prod/example"
```bash
kubectl apply -f ./overlays/prod/example
```
