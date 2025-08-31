Sistema Bancário em Python.

Este projeto é um sistema bancário orientado a objetos em Python, que permite gerenciar clientes, contas bancárias e transações (depósitos, saques e extratos). Ele utiliza conceitos importantes de POO como herança, polimorfismo, encapsulamento e abstração, além de boas práticas como iteradores, decoradores e classes abstratas.

Funcionalidades:

Cadastro de clientes (com CPF, nome, data de nascimento e endereço).
Abertura de contas correntes (associadas a um cliente).
Depósitos e saques com regras de limite e controle de saques diários.
Exibição de extrato bancário com histórico de transações.
Listagem de contas registradas.
Controle de transações diárias, limitando a quantidade máxima.
Histórico detalhado com data e hora de cada movimentação.

Regras de Negócio:

Cada cliente pode ter várias contas.
É possível realizar até 2 transações por dia (definido em Cliente).
Cada conta corrente permite até 50 saques (ajustável).
Cada saque não pode ultrapassar R$ 500,00 (valor padrão do limite).
Depósitos e saques inválidos são rejeitados com mensagens de erro.
