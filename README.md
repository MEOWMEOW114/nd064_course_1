# nd064_C1

# argocd

https://argo-cd.readthedocs.io/en/stable/getting_started/#4-login-using-the-cli
➜ nd064 kubectl port-forward svc/argocd-server -n argocd 8080:80
-> kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d

docker tag local-image:tagname new-repo:tagname
docker push new-repo:tagname
2405 docker build -t techtrends .
2406 docker run -p 7111:3111 techtrends
2407 docker run -p 7112:3111 techtrends
docker push leehc114/nd064_course_1:v1.0.0
kubectl port-forward svc/argocd-server -n argocd 8080:80
2374 kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d\n

# build with tag

- docker build -t techtrends .
