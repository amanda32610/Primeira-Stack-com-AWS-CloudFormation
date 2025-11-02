# Implementando sua Primeira Stack com AWS CloudFormation


# 📌 Descrição do Projeto

Este projeto foi realizado como parte do desafio da DIO para consolidar conhecimentos em AWS CloudFormation.
O objetivo foi criar uma Stack automatizada que provisiona recursos na AWS de forma declarativa e documentar todo o processo de implementação.

A Stack criada neste laboratório inclui:

Uma instância EC2 do tipo t2.micro

Um Security Group permitindo acesso SSH

# 🛠️ Tecnologias Utilizadas

AWS CloudFormation – Criação da Stack e provisionamento de recursos

AWS EC2 – Instância virtual

AWS Security Groups – Controle de acesso à instância

AWS Console – Monitoramento e testes da Stack

# 🏗️ Arquitetura da Stack
[Security Group] ←→ [EC2 Instance]

Explicação:

EC2 Instance (t2.micro): Máquina virtual criada automaticamente pela Stack

Security Group: Grupo de segurança que permite acesso SSH (porta 22)

Os recursos são totalmente provisionados e gerenciados pelo CloudFormation, garantindo replicabilidade e automação

# 📄 Arquivo JSON do Template

O template da Stack está no arquivo my-first-stack.json, que pode ser usado diretamente no AWS CloudFormation.


# 🧠 Insights e Aprendizados

Entendi como o CloudFormation provisiona recursos de forma declarativa

Aprendi a criar Stacks reutilizáveis e versionadas

Compreendi a importância do controle de acesso via Security Groups

Aprendi a documentar a infraestrutura de forma clara para estudos futuros

Percebi que modificações na Stack podem ser aplicadas de forma segura via atualização

📂 Estrutura do Repositório
│── README.md
└── my-first-stack.json



👩‍💻 Autora

Projeto desenvolvido por Amanda Justen — Engenharia de Computação & IA
LinkedIn: linkedin.com/in/amanda-justen-80b17182
