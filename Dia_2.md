# #30DiasDeAWS

## Dia 2

Olá, estou iniciando o projeto **#30DiasDeAWS** para ajudar a organizar os meus estudos para a certificação **AWS Cloud Practitioner** que pretendo fazer no final dos 30 dias de desafio. 

Sou a Ana Luiza, trabalho com cloud desde 2020, minha primeira experiência foi com GCP (Google Cloud Platform) e desde 2021 estou no mundo AWS trabalhando em um banco laranja beeem conhecido por todos, aquele que começa com "i" (uma charada, tem duas alternativas). 

Aqui vou postar meu progresso de estudos independente para fixar melhor os conceitos. Espero que esse material sirva para ajudar mais alguém a passar no exame também.

## 2.1 - Messaging e Queuing

**Conceitos de arquitetura**

### Tightly Coupled Architecture
 - Se uma parte da aplicação falhar, todas falham quando tentam se conectar com ela. Exemplo: aplicações monolíticas.

### Loosely Coupled Architecture
 - Uma falha em qualquer parte da aplicação não causa outras falhas. Exemplo: aplicações de microserviço. 

## 2.2 - Amazon Simple Queue Service (Amazon SQS)

 - Enviar mensagens
 - Armazenar mensagens 
 - Receber mensagens

 ... entre componentes de software de qualquer volume.

**Payload** é o dado que contém todas as mensagens.

**SQS queues** é o local onde as mensagens são armazenadas até serem processadas. 

## 2.3 - Amazon Simple Notification Service (Amazon SNS)

 - Modelo Pub/Sub (publish/subscribe service)
 - Pode enviar mensagens via:
   - mobile push
   - SMS
   - e-mail

**SNS Topic** é o canal para as mensagens serem entregues. 

No Amazon SNS, um publicador publica mensagens para inscritos utilizando o SNS Topic.  

## 2.4 - AWS Lambda

o AWS Lambda é o serviço no qual não há necessidade de provisionar ou gerencias servidores (serverless).

Ele serve para:
 - Hospedar funções executáveis simples
 - Apps orientadas a serviço
 - Apps dirigidas a eventos

> Serverless: you cannot see or access the underlying infrastructure. 

Como funciona: 

 - Você carrega seu código para a Lambda
 - Você define seu código para triggar a partir de uma fonte de eventos, como serviços da AWS, aplicativos mobile ou endpoints HTTP
 - A Lambda executa seu código somente quando triggado
 - Você paga apenas pelo tempo de recurso utilizado

## 2.5 - Containers

Os contêineres fornecem uma maneira padrão de empacotar o código e as dependências do seu aplicativo em um único objeto. Você também pode usar contêineres para processos e fluxos de trabalho nos quais há requisitos essenciais de segurança, confiabilidade e escalabilidade.

**Orquestração de Container**

A orquestração de container ajuda a deployar, gerenciar e escalar as aplicações containerizadas. 

## 2.6 - Amazon Elastic Container Servive (ECS)

O Amazon Elastic Container Service é um sistema de gerenciamento de containers de alta performance, altamente escalável, que habilita executar e escalar aplicações containerizadas na AWS. 

> O Amazon ECS oferece suporte a contêineres do Docker. O **Docker** é uma plataforma de software que permite criar, testar e implantar aplicativos rapidamente. A AWS oferece suporte ao uso do Docker Community Edition de código aberto e do Docker Enterprise Edition baseado em assinatura. Com o Amazon ECS, você pode usar chamadas de API para iniciar e interromper aplicativos habilitados para Docker.

## 2.7 - Amazon Elastic Kubernetes Service (EKS)

O Amazon Elastic Kubernetes Service é o serviço para executar o kubernetes na AWS. 

> O **Kubernetes** é um software de código aberto que permite implantar e gerenciar aplicativos em contêiner em escala. Uma grande comunidade de voluntários mantém o Kubernetes, e a AWS trabalha ativamente em conjunto com a comunidade do Kubernetes. À medida que novos recursos e funcionalidades são lançados para aplicativos do Kubernetes, você pode aplicar facilmente essas atualizações aos seus aplicativos gerenciados pelo Amazon EKS.

## 2.8 - AWS Fargate

O AWS Fargate é um motor serverless para containers. É uma plataforma computacional serverless para ECS e EKS. Ele gerencia a infraestrutura para você se preocupar apenas com a aplicação. 