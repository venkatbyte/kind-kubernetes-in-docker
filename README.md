# kind-kubernetes-in-docker
# To get all contexts (kubernetes clusters in config)
kubectl config get-contexts
# To check current context(Cluster)
kubectl get current-context
# To change context to different
kubectl config get-contexts  
kubectl config use-context docker-desktop
# To delete context from config
kubectl config delete context docker-desktop

#kubectl Quick Reference
https://kubernetes.io/docs/reference/kubectl/quick-reference/
