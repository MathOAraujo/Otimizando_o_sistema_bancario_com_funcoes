# Desafio: Otimizando o Sistema Bancário com funções
Link do [Sistema Bancário anterior](https://github.com/MathOAraujo/Criando_um_sistema_bancario/tree/main).

## Objetivo Geral

Separar as funções existentes de saque, depósito e extrato em funções. Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.

## Desafio

Deixar o código do [desafio anterior](https://github.com/MathOAraujo/Criando_um_sistema_bancario/tree/main) mais modularizado, para isso devo criar funções para as operações existentes: sacar, depositar e visualizar extrato. Além disso, para a versão 2 do sistema preciso criar duas novas funções: criar usuário (cliente do banco) e criar conta corrente (vincular com usuário).

### Separação em funções

Deve criar funções para todas as operações do sistema. Cada função vai ter uma regra na passagem de argumentos. O retorno e a forma como são chamadas, pode ser definida por da forma que achar melhor.

### Saque

A função saque deve receber os argumentos apenas por nome (keyword only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

### Depósito

A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato.

### Extrato

A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais: saldo. Argumentos nomeados: extrato.

### Criar usuário (cliente)

O programa deve armazenar os usuários em uma lista, um usuário é composto por: nome, data de nascimento, CPF e endereço. O endereço é uma string com formato: logradouro, número - bairro - cidade/sigla do estado. Deve ser armazenado somente os números do CPF. Não podemos cadastrar 2 usuários com o mesmo CPF.

### Criar conta corrente

O programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente a um usuário.


