# Relatório de Testes de API — Projeto 01

## 1. Objetivo

Validar o comportamento de endpoints de uma API REST por meio de requisições HTTP e testes automatizados no Postman, verificando códigos de status, estrutura das respostas JSON e consistência dos dados retornados.

## 2. Ambiente de teste

- **Ferramenta:** Postman
- **API:** JSONPlaceholder
- **Endpoint base:** `https://jsonplaceholder.typicode.com`
- **Tipo de teste:** Testes funcionais de API
- **Formato de dados:** JSON

## 3. Escopo dos testes

Foram elaborados e executados testes para os seguintes cenários:

| ID | Método | Cenário | Resultado |
|---|---|---|---|
| API-01 | GET | Listar usuários | Aprovado |
| API-02 | GET | Consultar usuário inexistente | Aprovado |
| API-03 | POST | Criar usuário | Aprovado |
| API-04 | PATCH | Atualizar nome do usuário | Aprovado |
| API-05 | PUT | Substituir dados do usuário | Aprovado |
| API-06 | DELETE | Excluir usuário | Aprovado |

## 4. Validações realizadas

- Verificação dos códigos de status HTTP esperados.
- Validação do formato e da estrutura das respostas JSON.
- Conferência da quantidade de usuários retornados na listagem.
- Verificação da presença de campos obrigatórios, como `id`, `name` e `email`.
- Validação dos dados retornados nas operações de criação e atualização.
- Verificação da resposta da consulta a um usuário inexistente.
- Validação da resposta da operação de exclusão.

## 5. Resultado da execução

Os testes automatizados configurados para os seis cenários foram aprovados durante a execução no Postman.

**Status geral:** Aprovado.

## 6. Observações e limitações

O JSONPlaceholder é uma API pública destinada a testes e demonstrações. As operações de criação, atualização e exclusão simulam respostas, mas não persistem alterações reais nos dados.

Os resultados demonstram a execução dos cenários previstos nesse ambiente de teste e não representam uma validação completa de uma API de produção.

## 7. Ferramentas e conhecimentos aplicados

- Postman e coleções de requisições
- Métodos HTTP: GET, POST, PATCH, PUT e DELETE
- APIs REST
- Validação de status codes
- Testes automatizados com scripts JavaScript
- Análise de respostas JSON
- Documentação de testes funcionais

## 8. Artefato

A coleção exportada do Postman está disponível no arquivo JSON deste diretório e pode ser importada no Postman para consultar e executar as requisições.

