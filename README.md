# Kubernetesについて

## kubectlインストール
```
brew install kubectl
alias k=kubectl
k version
```

## Ubuntu起動
```
k run --image ubuntu -it ubuntu -- bash
```

## getコマンドについて
```
k get all
```

## Podについて
```
k get po
k apply -f pod.yaml
```

## Replica Setについて
```
k get rs
k apply -f replica_set.yaml
```

## Deploymentについて
```
k get rs
k apply -f deployment.yaml
```

## Serviceについて
```
k get svc
k apply -f service.yaml
```

## Ingressについて
```
k get ing
k apply -f ingress.yaml
```
