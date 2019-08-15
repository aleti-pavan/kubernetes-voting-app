# kubernetes-voting-app
This repo has manifests of k8s Pods, Services of voting apps. This doesn't contain Deployments and Deployments should be following into another repository


We are using existing docker images of voting app and deploying that onto kubernetes

Instructions to deploy.

Clone the repository

`1. git clone https://github.com/aleti-pavan/kubernetes-voting-app.git`


Get on to kubernetes cluster and execute following command to see if any of the pods running.

`2. kubectl get pods -o wide`

Get into the folder

`3. cd kubernetes-voting-app/`

deploy k8s manifests

`4. kubectl apply -f .`
