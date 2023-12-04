# Flask_devops проект в k8s.

---

## Цель: запустить в Kubernetes flask-приложение.

## Выполнение.

Предварительно: установлен и настроен кластер minikube, собран образ flask-приложения и залит на DockerHub.

---

![dockerhub](/img/dockerhub.jpg "Репозиторий DockerHub.")


Далее, написан Deployment и Service.

---

### flask-deployment.yaml.

![deployment](/img/deployment.jpg "Deployment в VSC.")

---

### flask-service.yaml.

![service](/img/service.jpg "Service в VSC.")

Проверяем наличие функционирующего пода, deployment-а и сервиса в Lens.

---

### Deployment в Lens.

![deployments](/img/deployments.jpg "Deployments в Lens.")

---

### Работающий service в Lens.

![Services](/img/Services.jpg "Services в Lens.")

---

### Работающий pod в Lens.

![pods](/img/pods.jpg "Pods в Lens.")


Проверяем, работает ли наше приложение.

---

### Работающее flask-приложение.

![ready](/img/ready.jpg "Работающее flask-приложение.")
