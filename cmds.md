 kubectl get pods
 kubectl get svc
 helm repo add grafana https://grafana.github.io/helm-charts\n\n
 helm repo update\n\n
 helm install grafana grafana/grafana\n\n
 kubectl expose service grafana — type=NodePort — target-port=3000 — name=grafana-ext\n\n
 kubectl expose service grafana —-type=NodePort —-target-port=3000 —-name=grafana-ext\n\n
 kubectl expose service grafana --type=NodePort --target-port=3000 --name=grafana-ext
 minikube get service
 kubectl get service
 minkube service prometheus-server-ext
 minikube service prometheus-server-ext
 minikube service grafana-ext
 minikube ip
