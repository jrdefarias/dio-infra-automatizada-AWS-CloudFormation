# Desafio DIO - Implementando Infraestrutura Automatizada com AWS CloudFormation

## Introdução

Neste desafio tive meu primeiro contato prático com o AWS CloudFormation, um serviço da AWS que permite criar e gerenciar recursos de infraestrutura através de código.

O objetivo da atividade foi compreender como a automação pode facilitar a criação de ambientes na nuvem, evitando configurações manuais e permitindo que a mesma infraestrutura seja recriada sempre que necessário de forma padronizada.

Durante o laboratório pude entender melhor o conceito de Infraestrutura como Código (IaC) e a importância dessa abordagem em ambientes corporativos.

---

## O que é AWS CloudFormation?

O AWS CloudFormation é um serviço que permite definir recursos da AWS utilizando arquivos de texto nos formatos JSON ou YAML.

Com ele é possível automatizar a criação de diversos componentes, como:

* Instâncias EC2
* Redes VPC
* Security Groups
* Buckets S3
* Bancos de dados
* Balanceadores de carga

Ao invés de criar cada recurso manualmente pelo console da AWS, podemos descrever toda a infraestrutura em um template e executá-la de forma automatizada.

---

## Conceitos Aprendidos

### Infraestrutura como Código (IaC)

Infraestrutura como Código é uma prática que permite gerenciar recursos através de arquivos de configuração.

Entre as principais vantagens estão:

* Padronização dos ambientes
* Redução de erros humanos
* Facilidade de replicação
* Controle de versão utilizando Git e GitHub
* Maior agilidade na implantação

### Templates

Os templates são arquivos que descrevem toda a infraestrutura que será criada.

No CloudFormation os templates normalmente são escritos em YAML ou JSON.

### Stack

Uma Stack é o conjunto de recursos criados a partir de um template.

Ao criar uma Stack, o CloudFormation interpreta o template e provisiona todos os recursos necessários automaticamente.

---

## Etapas Realizadas

### 1. Acesso ao AWS CloudFormation

Primeiramente acessei o console da AWS e naveguei até o serviço CloudFormation.

### 2. Análise do Template

Durante a aula foi apresentado um template contendo a definição da infraestrutura.

Observei a estrutura do arquivo e identifiquei elementos importantes como:

* Resources
* Parameters
* Outputs

### 3. Criação da Stack

Utilizando o template fornecido, foi criada uma Stack através do console da AWS.

Durante esse processo foi possível acompanhar a criação automática dos recursos.

### 4. Validação

Após a implantação, verifiquei se todos os recursos foram criados corretamente e analisei os eventos gerados pelo CloudFormation.

---

## Conclusão

Este laboratório foi importante para consolidar os conhecimentos introdutórios sobre AWS CloudFormation e Infraestrutura como Código.

A experiência permitiu compreender como a automação pode simplificar a administração de ambientes em nuvem, além de demonstrar a importância da documentação e do versionamento dos projetos.

---

## Referências

* Documentação oficial da AWS CloudFormation
