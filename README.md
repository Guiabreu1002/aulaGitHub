# Sistema Bancário
Este é um sistema bancário básico desenvolvido em Java, que permite gerenciar clientes, contas, cartões e realizar transações bancárias. O sistema suporta a criação de contas correntes e poupanças, bem como a gestão de cartões associados a essas contas.

Funcionalidades
Cadastro de Clientes: Permite criar clientes com nome e senha.
Criação de Contas: Possibilidade de criar contas correntes e poupanças para os clientes.
Gerenciamento de Cartões: Cada cliente pode ter até 3 cartões associados, incluindo cartões de conta corrente e poupança.
Transações Bancárias: Realização de saques e depósitos em contas correntes e poupanças, com verificação de saldo.
Segurança de Acesso: Verificação de nome e senha para realizar transações.
Estrutura do Projeto
O projeto é organizado em várias classes principais:

Banco: Gerencia os clientes e suas contas. Possui métodos para realizar saques, depósitos e gerenciar cartões.
Cliente: Representa um cliente do banco, contendo informações pessoais, como nome, senha e seus cartões associados.
Conta (Abstrata): Classe base abstrata para ContaCorrente e ContaPoupanca, definindo métodos comuns, como sacar e depositar.
ContaCorrente: Extende Conta e possui funcionalidades específicas, como limite de crédito.
ContaPoupanca: Extende Conta com funcionalidades específicas para poupança.
Cartao: Representa um cartão associado a uma conta, com atributos como número, marca, tipo (corrente ou poupança).
