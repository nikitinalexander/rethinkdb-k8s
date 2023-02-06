# rethinkdb-k8s

setup

edit base/secret.yml and set the desired password (should be base64)

deploy:

kubectl apply -k overlays/dev

cleanup:

kubectl delete -k overlays/dev