# Projeto 01 — Testes Funcionais Web | SauceDemo

## Sobre o projeto

Projeto de testes funcionais realizado na aplicação web **SauceDemo**, com o objetivo de validar os principais fluxos de uma aplicação de e-commerce, desde a autenticação até a finalização de um pedido.

Os testes foram executados manualmente, com documentação dos cenários, resultados obtidos e status de execução.

## Objetivos

* Validar o funcionamento dos principais recursos da aplicação.
* Identificar comportamentos inesperados durante a execução dos testes.
* Validar regras de negócio e fluxos de navegação.
* Documentar casos de teste e resultados.
* Garantir a integridade do fluxo de compra.

## Escopo dos testes

Foram testados os seguintes módulos:

* Login e autenticação
* Catálogo de produtos
* Ordenação de produtos
* Detalhes dos produtos
* Carrinho de compras
* Checkout
* Validação de campos obrigatórios
* Resumo do pedido
* Finalização da compra
* Cancelamento do checkout
* Logout
* Controle de sessão

## Resultados

**37 casos de teste executados**

**37 casos aprovados**

**0 casos reprovados**

**Taxa de aprovação: 100%**

## Tipos de validação

Durante a execução foram realizadas validações de:

* Fluxos positivos
* Fluxos negativos
* Validação de campos obrigatórios
* Mensagens de erro
* Navegação entre páginas
* Persistência dos dados do carrinho
* Cálculo e apresentação dos valores do pedido
* Controle de sessão após logout

## Técnicas e ferramentas

* Testes funcionais manuais
* Elaboração de casos de teste
* Testes positivos e negativos
* Validação de regras de negócio
* Análise de resultados
* Documentação de evidências
* GitHub
* SauceDemo

## 📁 Estrutura do projeto

```text
projeto-01-saucedemo/
├── README.md
├── casos-de-teste/
│   └── casos-de-teste-saucedemo.xlsx
├── evidencias/
│   ├── login/
│   ├── produtos/
│   ├── carrinho/
│   └── checkout/
└── bugs/
```

## 📋 Documentação

Os casos de teste completos estão disponíveis na planilha:

**[Casos de Teste — SauceDemo](./casos-de-teste/casos%20de%20testes.xlsx)**

## Próximas etapas

Como evolução deste projeto, alguns dos cenários funcionais serão automatizados utilizando **Playwright**, permitindo demonstrar a integração entre testes manuais e automação de testes.

---

**Projeto desenvolvido para demonstração prática de conhecimentos em Quality Assurance (QA).**

