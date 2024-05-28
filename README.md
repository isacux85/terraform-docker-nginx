#Terraform en local con docker
Receta para desplegar un contendor docker con nginx

Previo: 

Tener instalado en local docker: https://docs.docker.com/engine/install/ubuntu/

Tener instalado terraform: https://developer.hashicorp.com/terraform/tutorials/docker-get-started/install-cli

Clonar proyecto y parado en el mismo, abrir terminal

Ejecutar:

- "terraform init"

- "terrafom plan"

- "terraform apply -auto-approve"

ir a browser y poner en la url: http://localhost:8080

Eliminar todo:

- "terraform destroy -auto-approve"
