# argo-applications
# namespaces
kubectl apply -f argo-application-namespaces.yaml -n argocd
# sealed-secret
kubectl apply -f argo-application-kubeseal.yaml -n argocd
# starboard-operator
kubectl apply -f argo-application-starboard-operator.yaml -n argocd
# starboard-cli-cronjob
kubectl apply -f argo-application-starboard-cli-cronjob.yaml -n argocd
# starboard-exporter
kubectl apply -f argo-application-starboard-exporter.yaml -n argocd
# prometheus-grafana-alertmanager
kubectl apply -f argo-application-prometheus-grafana.yaml -n argocd