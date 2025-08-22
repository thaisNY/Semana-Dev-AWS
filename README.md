# Semana-Dev-AWS

# Projeto Pedidos AWS

### Apresentação do Projeto

Neste projeto, eu construí uma arquitetura AWS completa e funcional, explorando diversos serviços serverless e orientados a eventos. Durante quatro aulas intensas, eu desenvolvi cada etapa do pipeline de pedidos, desde a entrada dos dados até o processamento e persistência.

![Descrição da Imagem](https://raw.githubusercontent.com/thaisNY/Semana-Dev-AWS/main/imgs/layout.png)
---

### O que foi feito em cada aula

* **Aula 1**: Criei a porta de entrada principal usando **API Gateway** e iniciei o pipeline com **SQS** e **EventBridge**.
* **Aula 2**: Implementei um fluxo de ingestão de arquivos via **S3**, integrando-o de forma inteligente ao pipeline principal.
* **Aula 3**: Desenvolvi o processamento central que consome eventos do **EventBridge** e persiste os pedidos no **DynamoDB**.
* **Aula 4**: Adicionei fluxos de cancelamento e alteração, além de implementar o tratamento de erros com **DLQs**.

---

### Arquitetura que construí

A arquitetura que criei é **serverless**, **desacoplada** e **orientada a eventos**, capaz de lidar com múltiplas fontes de dados e diferentes operações de negócio.

#### Serviços AWS utilizados

* **Compute**: AWS Lambda
* **Integração**: Amazon API Gateway, Amazon SQS (Standard e FIFO), Amazon EventBridge, Amazon SNS
* **Armazenamento**: Amazon S3, Amazon DynamoDB
* **Gerenciamento e Governança**: AWS IAM, AWS CloudWatch (Logs e Métricas)

---

### Reflexão sobre o aprendizado

Foram quatro dias intensos, repletos de prática, configurações e desafios. Cada erro que encontrei e resolvi foi uma oportunidade de aprendizado.

Sinto que construí algo **complexo e funcional**, peça por peça, e que minha persistência e curiosidade foram essenciais para chegar até aqui. Este projeto me proporcionou uma **base sólida para continuar explorando o universo da AWS** e me dá confiança para enfrentar novos desafios em nuvem.

Estou animada para continuar aprendendo, experimentando e construindo coisas incríveis com a AWS!
