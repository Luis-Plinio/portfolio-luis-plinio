r# 🏢 Auditoria de Orçamentos Corporativos (Python)
 
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen.svg)]()
 
## 📖 Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina de Programação de computadores do curso de Ciência da computação. O objetivo do script é processar e calcular o orçamento de uma estrutura organizacional complexa (dicionários aninhados) de uma multinacional, aplicando regras de negócio dinâmicas e auditoria de execução.
 
A solução foi arquitetada utilizando conceitos avançados de Python para garantir flexibilidade, performance e rastreabilidade.
 
## 🚀 Funcionalidades
- **Cálculo Hierárquico:** Varredura completa da estrutura corporativa, independentemente do nível de profundidade.
- **Filtros Dinâmicos:** Capacidade de ignorar setores específicos e todos os seus subsetores na hora do cálculo financeiro.
- **Conversão de Câmbio:** Suporte a parâmetros opcionais para conversão de moedas em tempo de execução.
- **Sistema de Auditoria:** Monitoramento automatizado de tempo de execução e registro (logging) dos parâmetros utilizados na transação financeira.
 
## 🛠️ Tecnologias e Conceitos Aplicados
Este projeto foi construído utilizando Python puro (Standard Library), com foco nos seguintes paradigmas e recursos:
* **Funções Recursivas (Recursion):** Utilizadas para a navegação na árvore de dados (dicionários aninhados).
* **Decorators:** Implementação do `@auditor` para injetar comportamentos de log e cronometragem sem modificar a lógica de negócios.
* **Empacotamento de Argumentos (`*args` e `**kwargs`):** Utilizados tanto no decorator quanto na função principal para permitir a passagem dinâmica de departamentos a serem ignorados e taxas de câmbio.
 
## ⚙️ Como Executar
 
### Pré-requisitos
* Python 3.8 ou superior instalado.
 
### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone [https://github.com/Luis-Plinio](https://github.com/Luis-Plinio/projeto_sistema_de_auditoria.git)
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd projeto_sistema_de_auditoria
   ```
3. Execute o script principal:
   ```bash
   sistema_de_auditoria main.py
   ```
 
## 🧠 Lógica e Estrutura do Código
Breve explicação de como o código foi organizado:
* `Eu organizei o código separando a auditoria, os dados da empresa e o cálculo do orçamento. Usei recursão para percorrer todos os setores do dicionário e somar os valores automaticamente, mesmo com vários níveis. Também utilizei *args para ignorar departamentos e **kwargs para configurar moeda e taxa de câmbio.`.
* **Dados:** Os dados simulados da empresa foram estruturados em... `JSON`.
 
## 👤 Autor
 
* **Luis Plinio Cornelio Mota** * LinkedIn: https://www.linkedin.com/in/luis-plinio-corn%C3%A9lio-mota-84a438363/
* E-mail: luispliniocmota@gmail.com
 
---
*Projeto acadêmico com foco na aplicação prática de conceitos avançados da linguagem Python.*
