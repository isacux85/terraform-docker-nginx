
#Terraform en local con docker
====================

Proyecto para practicar terraform y desplegar contenedores docker.
Es un primer acercamiento a la herramienta de terrfaorm desplegando contenedores docker, en este ejemplo se levanta un nginx.

Previo: 

Tener instalado en local docker: https://docs.docker.com/engine/install/ubuntu/

Tener instalado terraform: https://developer.hashicorp.com/terraform/tutorials/docker-get-started/install-cli

Clonar proyecto y parado en el mismo abrir terminal

Ejecutar en terminal:

terraform init

terrafom plan

terraform apply -auto-approve

ir a browser y poner en la url: http://localhost:8080

terraform destroy -auto-approve
