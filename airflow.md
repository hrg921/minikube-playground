# airflow on minikube

`brew install minikube`

`kubectl create namespace dev`

`brew instal helm`

`helm repo add stable https://charts.helm.sh/stable --force-update`

`helm install airflow-test stable/airflow --version "7.1.5" -n dev`
