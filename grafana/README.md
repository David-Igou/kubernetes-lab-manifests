helm repo add stable https://kubernetes-charts.storage.googleapis.com
helm repo update
helm upgrade --install grafana stable/grafana -n grafana --set ingress.enabled=true
