# atividade_kubernetes

Quarta atividade do curso Infrastructure and Cloud Computing 

Professor: João Victorino

## Alunos:

Leonardo Ananias do Nascimento Azogue 

Vinissius Vioti dos Santos 

## ***Descrição Atividade:*** 
Subir dois pods, nginx e mysql, mapeando a porta 80 do nginx para acesso externo ao cluster e permitir que o contêiner do nginx 
tenha comunicação de rede no contêiner mysql pela porta 3306. A atividade pode ser feita localmente (minikube), AKS (Azure), EKS (AWS) ou no GKE (GCP). 
Se quiser criar o cluster nuvem Kubernetes com Terraform é opcional. Enviar os arquivos yaml pelo GitHub.

*Utilizado a imagem Ubunto Server 18.14, e utilizado Azure"*

> Passo a passo
```
Baixar o código no github https://github.com/leonasci02/terraform_apache_mysql.git
abra o Visual Code na pasta do projeto
Execute o comando:$ az login 
Execute o comando:$ Terraform init 
Execute o comando:$ Terraform plan
Execute o comando:$ Terraform apply (-auto-approve)
Execute o comando:$ ssh na VM principal ( pode ser pelo IP statico criado "10.0.2.12")
Execute o comando:$ mysql -u root -p na
Após o comando digite a senha:$ "teste123456"
Então será apresentado a mensagem: "Welcome to the MySQL monitor"

```
