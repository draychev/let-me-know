There are a few things that need to be install:

sudo sbopkg -i conmon
sudo sbopkg -i runc
sudo sbopkg -i go-md2man
sudo sbopkg -i podman
sudo sbopkg -i minikube



minikube start  --driver=podman


OR maybe install docker and docker-cli using sbopkg but only after you upgrade Go to 1.17
minikube start  --driver=docker
