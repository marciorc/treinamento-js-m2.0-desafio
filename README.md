# Pesquisa de Pessoas por CPF 🧑‍💻
**Desafio da Mentoria de Testes de Software 2.0**  
Projeto demonstrando uma função de pesquisa com testes unitários.

## 📋 Descrição
Este projeto contém uma função para pesquisar pessoas cadastradas por CPF, desenvolvida como parte dos desafios da Mentoria de Testes de Software 2.0.

## ⚙️ Funcionalidade Principal
`pesquisarPessoaPorCpf(cpf)`

Parâmetro: Recebe um CPF como string

Retornos possíveis: 
- Objeto completo da pessoa se encontrada
- String "CPF não encontrado" se não existir

## 🧪 Testes Implementados
O projeto inclui testes unitários para validar:

- Pesquisa por CPF existente
  - Retorno de dados corretos (nome, CPF e frutas favoritas)

- Tratamento para CPF não encontrado

## 🚀 Como Executar

1. Clone o repositório

2. Instale as dependências:
    `npm install`

3. Execute os testes:
    `npm test`
