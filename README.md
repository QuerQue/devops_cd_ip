# devops_cd_ip
first run: kubectl apply -f argo/application-set.yaml  
effect: two argocd Applications created, all required k8s manifests deployed, argocd monitor github repository and sync changes  
busybox:stable doesn't have java installed so spring argument is commented  
pod is using sleep command for testing purpose  
in dev/prd dirs values that override default values.yaml
