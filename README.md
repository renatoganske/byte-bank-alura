# Bytebank

Este repositório contém o projeto **Bytebank**, desenvolvido durante o curso de **Java e JDBC** da [Alura](https://www.alura.com.br/). No decorrer do curso, aprendemos sobre conceitos fundamentais como **DAO (Data Access Object)**, **Connection Factory**, entre outros. O projeto consiste na criação de um sistema bancário com diversas operações que podem ser realizadas em contas correntes.

## Funcionalidades

O Bytebank oferece as seguintes operações:

1. **Listar Contas Abertas**: Exibe todas as contas que estão atualmente ativas no banco.
2. **Abertura de Conta**: Permite a criação de uma nova conta bancária.
3. **Encerramento de Conta**: Permite o encerramento lógico de uma conta existente.
4. **Consulta de Saldo**: Exibe o saldo atual de uma conta específica.
5. **Realização de Saque**: Permite a retirada de dinheiro de uma conta.
6. **Realização de Depósito**: Permite o depósito de dinheiro em uma conta.
7. **Realização de Transferência**: Permite a transferência de dinheiro entre duas contas.

## Estrutura do Projeto

O projeto está organizado nas seguintes classes principais:

- **BytebankApplication**: Classe principal que contém o menu e as operações que podem ser realizadas.
- **Cliente**: Classe que representa um cliente
- **DadosCadastroCliente**: Classe que encapsula os dados do cliente.
- **Conta**: Classe que representa uma conta
- **DadosAberturaConta**: Classe que encapsula os dados necessários para a abertura de uma nova conta.
- **ContaService**: Classe que gerencia as operações de contas.
- **ContaDAO**: Classe responsável por encapsular todo o acesso aos dados relacionados às contas bancárias.
- **ConnectionFactory**: Classe responsável por gerenciar a criação de conexões com o banco de dados.
- **RegraDeNegocioException**: Exceção personalizada para tratar erros de regras de negócio.

## Estrutura do Código
O código utiliza a classe ContaService para realizar todas as operações relacionadas às contas. A interação com o usuário é feita através da classe BytebankApplication, que apresenta um menu interativo no console para escolha das operações disponíveis.

## Execução
Ao executar o programa, o usuário pode escolher entre várias opções no menu apresentado, cada uma correspondendo a uma operação específica no sistema bancário simulado.

### Exibição do Menu

            BYTEBANK - ESCOLHA UMA OPÇÃO:
            1 - Listar contas abertas
            2 - Abertura de conta
            3 - Encerramento de conta
            4 - Consultar saldo de uma conta
            5 - Realizar saque em uma conta
            6 - Realizar depósito em uma conta
            7 - Realizar transferência entre contas
            8 - Sair

## Pré-requisitos para Execução
Para executar o projeto, é necessário ter instalado:

JDK (Java Development Kit)
MySQL
As dependências necessárias especificadas no projeto (incluídas no pom.xml).
