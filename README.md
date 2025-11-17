init
kubectl create secret generic sops-age --namespace=flux-system --from-file=agekey=/home/theo/.config/sops/age/keys.txt
