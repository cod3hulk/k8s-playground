stop:
	minikube stop
	minikube delete

run:
	minikube start --addons ingress

apply:
	kubectl apply -f nginx-hello-namespace.yml
	kubectl apply -f nginx-hello-deployment.yml
	kubectl apply -f nginx-hello-ingress.yml

