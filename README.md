# homelab_drone


## Install Drone with Helm
```
helm repo add community-charts https://community-charts.github.io/helm-charts
helm repo update

kubectl create ns drone
helm install drone community-charts/drone -n drone
```

