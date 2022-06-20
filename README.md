## K8S

### Commands

#### kubectl:
- `kubctl get all`
- `kubectl apply --validate=true --dry-run=[client,server] -f ./`
- `kubectl apply -f [config_file.yaml]`
- `kubectl exec -it [name] sh`
- `kubectl describe [pod,rs] [name]`
- `kubectl delete [pod] --all`

#### minikube:
- `minikube start --vm-driver=hyperkit`
- `minikube status`
- `minikube ip`
- `minikube dashboard`
- `minikube service [service-name] --url`
