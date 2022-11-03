# #30DiasDeAWS

## Dia 1

Olá, estou iniciando o projeto **#30DiasDeAWS** para ajudar a organizar os meus estudos para a certificação **AWS Cloud Practitioner** que pretendo fazer no final dos 30 dias de desafio. 

Sou a Ana Luiza, trabalho com cloud desde 2020, minha primeira experiência foi com GCP (Google Cloud Platform) e desde 2021 estou no mundo AWS trabalhando em um banco laranja beeem conhecido por todos, aquele que começa com "i" (uma charada, tem duas alternativas). 

Aqui vou postar meu progresso de estudos independente para fixar melhor os conceitos. Espero que esse material sirva para ajudar mais alguém a passar no exame também.

Vamos começar com alguns conceitos básicos.

## 1.1 - Computação em Nuvem

É a entrega sob demanda de recursos de tecnologia da informação pela internet com pagamento no modelo pay-as-you-go.

Pay-as-you-go é um conceito chave para estudarmos nuvem e, principalmente, AWS. Isso significa que você só paga o que usar, ou seja, independente do recurso ou serviço, você paga para a AWS somente o tempo que fizer uso dele. 

*YOU ONLY PAY WHAT YOU USE*

## 1.2 - Modelos de entrega para Computação em Nuvem

### Cloud Based: 
 - Executa toda a aplicação na nuvem
 - Migra aplicações existentes para a nuvem
 - Projeta e constrói novas aplicações para a nuvem

### On-Premises:
 - Entrega recursos usando virtualização e ferramentas de gerenciamento de recursos
  - É uma nuvem privada (Private Cloud)

### Hybrid Cloud:
 - Conecta o que está cloud based com on-premises
 - Integra recursos da nuvem com recursos legados

## 1.3 - Modelo Cliente-Servidor

![Modelo cliente-servidor](images\444px-Cliente-Servidor.png)

Na computação, um cliente pode ser um navegador da Web, um aplicativo de desktop ou um app de celular com o qual uma pessoa interage para fazer solicitações a servidores de computador. Um servidor pode ser serviços como o Amazon Elastic Compute Cloud (Amazon EC2), um tipo de servidor virtual.

Por exemplo, suponha que um cliente solicite um artigo de notícias, a pontuação de um jogo online ou um vídeo do youtube. O servidor avalia os detalhes dessa solicitação e a atende retornando as informações ao cliente.

## 1.4 - Benefícios da Computação em Nuvem

 - Troca o investimento inicial por despesas variáveis ao longo do tempo
 - Parar os gastos em manutenção e execução de data centers
 - Parar de "adivinhar" capacidade
 - Grande economia de escala
 - Melhor velocidade e agilidade
 - Capacidade global em minutos

## 1.5 - Amazon Elastic Compute Cloud (EC2)

 - Servidores Virtuais
 - Altamente flexível
 - Ótimo custo benefício
 - Rapidez e agilidade

O serviço Amazon EC2 utiliza o modelo **Multitenancy** *(multiplos inquilinos)*, compartilha de um hardware entre várias máquinas/servidores virtuais. 

### Configurações permitidas nas Instâncias EC2

 - Windows
 - Linux
 - Aplicações Corporativas
 - Web Apps
 - Banco de Dados
 - Softwares terceirizados

Outro conceito importante da Amazon EC2 é o **Vertical Scaling**, significa que as instâncias são facilmente escaláveis e redimensionáveis. 

## 1.6 - Tipos de Instâncias EC2

Cada tipo de instância EC2 é agrupada dentro de uma família de instâncias. 

*Estou colocando os nomes sem tradução para melhor entendimento dos conceitos na hora da prova.*

### Famílias de Instâncias EC2

 - General purpose
 - Compute optimized
 - Memory optimized
 - Accelerated computing
 - Storage optimized

### Opções de pagamento

 - On-demand
 - Saving Plans
 - Reserved instances
 - Spot instances
 - Dedicated hosts

 