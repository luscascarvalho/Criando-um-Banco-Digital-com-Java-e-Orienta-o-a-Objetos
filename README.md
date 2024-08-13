# Banco Digital - Java e Orientação a Objetos

Este projeto é uma simulação simples de um banco digital, implementada em Java utilizando conceitos de Programação Orientada a Objetos (POO). O sistema oferece dois tipos de contas bancárias: **Conta Corrente** e **Conta Poupança**. As contas possuem funcionalidades básicas como depósito, saque e transferência entre contas.

## Funcionalidades

- **Depósito**: Adiciona um valor ao saldo da conta.
- **Saque**: Subtrai um valor do saldo da conta, caso haja saldo suficiente.
- **Transferência**: Transfere um valor de uma conta para outra, se houver saldo disponível.
- **Extrato**: Exibe o saldo e outras informações da conta.

## Estrutura do Projeto

- **Cliente**: Representa um cliente do banco.
- **Conta**: Classe abstrata que define as propriedades e métodos comuns a todas as contas.
- **ContaCorrente**: Classe que herda de `Conta` e representa uma conta corrente.
- **ContaPoupanca**: Classe que herda de `Conta` e representa uma conta poupança.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação utilizada para desenvolver o sistema.

## Como Executar

1. Clone o repositório para sua máquina:
    ```bash
    git clone https://github.com/luscascarvalho/Criando-um-Banco-Digital-com-Java-e-Orienta-o-a-Objetos
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd banco-digital
    ```

3. Compile o projeto:
    ```bash
    javac Main.java
    ```

4. Execute o projeto:
    ```bash
    java Main
    ```

## Exemplo de Uso

Ao executar o programa, ele realizará as seguintes operações:

- Criação de uma `ContaCorrente` para João e uma `ContaPoupanca` para Maria.
- Depósito de R$1000 na conta corrente de João e R$2000 na conta poupança de Maria.
- Saque de R$200 da conta corrente de João e R$500 da conta poupança de Maria.
- Transferência de R$300 da conta corrente de João para a conta poupança de Maria.
- Impressão dos extratos das contas de João e Maria.

