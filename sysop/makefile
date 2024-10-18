kompose:
	kompose convert -f docker-compose.yml -o k8s --namespace hcmus-final

uninstall:
	docker compose down
	docker image rm vochitrung/myid      

apply:
	kubectl apply -f k8s/

remove:
	kubectl delete deployments --all -n hcmus-final

update:
	kubectl delete deployments --all -n hcmus-final
	kubectl apply -f k8s/

start_kube:
	minikube start --driver=docker