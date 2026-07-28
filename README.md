# Terraform AWS - S3 Bucket

meu primeiro projeto utilizando Terraform para provisionar infraestrutura na AWS

## Objetivo

Criar um bucket S3 utilizando Infraestructure as Code (IaC) com Terraform.

## Tecnologias

- Terraform
- AWS
- Amazon S3
- VS Code
- WSL3

## Recursos criados

- Amazon S3 Bucket
- Tags padrão
- Proviter AWS (sa-east-1)

## Estrutura

|------main.tf |------bucket.tf |------.gitignore |------README.md

## Como executar

'''bash
terraform init
terraform plan
terraform apply

## Como remover

terraform destroy

Observações
As credencias da AWS não fazem parte deste repositório. Elas são configuradas por variáveis de ambiente.
