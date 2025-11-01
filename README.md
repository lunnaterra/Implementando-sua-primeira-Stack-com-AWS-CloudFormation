# AWS CloudFormation - Desafio DIO

## Descrição do Projeto
Este repositório contém um template CloudFormation criado como parte do desafio da DIO. O objetivo é demonstrar a criação de uma stack com recursos básicos na AWS de forma automatizada.

## Estrutura do Repositório
- `README.md`: documentação do projeto

## Recursos Criados
1. Bucket S3 (`MeuBucketS3`)
2. Instância EC2 (`MinhaInstanciaEC2`)
3. Security Group (`MeuSecurityGroup`) permitindo SSH

## Passos para Deploy
1. Fazer login no Console AWS ou via AWS CLI.
2. Navegar até o CloudFormation e criar stack.
3. Selecionar o template `minha_stack.yaml`.
4. Preencher parâmetros (ex: KeyName para acesso SSH).
5. Criar stack e aguardar a finalização.
6. Verificar os recursos criados no console.

## Aprendizados
- Criação de infraestrutura como código usando CloudFormation.
- Estruturação de templates YAML para múltiplos recursos.
- Versionamento de templates em repositórios Git.

