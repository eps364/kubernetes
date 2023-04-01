https://grafana.com/docs/grafana/latest/setup-grafana/installation/kubernetes/

kubectl apply -f grafana.yaml

kubectl port-forward service/grafana 3000:3000

localhost:3000

Use *admin* for both the username and password to login.