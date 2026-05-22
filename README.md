# 📂 Meu Projeto Git - Estudos em Python

**Este repositório foi criado para documentar e organizar minha evolução nos estudos de programação com Python e lógica de dados.**

---

  ### 🔑 1. Sistema de Validação de Senha (`Validacao_senha_while.ipynb`)
- Este script simula um sistema básico de segurança para validação de acesso com limite de erros.

- Laço de Repetição (`while`): Mantém o programa rodando até a condição de parada.
- Estruturas Condicionais (`if`, `elif`, `else`): Validam a senha e monitoram os erros.
- Controle de Fluxo (`break`): Interrompe o loop imediatamente ao liberar o acesso ou bloquear.

---

  ### 🧮 2. Calculadora Interativa (`Calculadora_Python_While.ipynb`)
- Uma calculadora completa que roda em loop e possui validação de dados para impedir que o usuário digite opções inválidas no menu.

---

  ### 🗄️ 3. Integração com Banco de Dados (`Sqlite_teste.ipynb`)
- Projeto focado na manipulação de dados utilizando Python integrado ao banco de dados SQLite.

---

  ### 4. Diário de Estudos em Python ('Diário_Estudo_Python.ipynb')
- Este é um projeto simples em linha de comando desenvolvido em Python para consolidar meus aprendizados iniciais na linguagem.

---

**O que o projeto faz:**
- **Registrar Estudos:** Permite salvar o nome da matéria estudada e o tempo dedicado.
- **Tratamento de Erros:** O sistema valida se o usuário digitou números ou letras na hora de informar as horas, evitando que o programa trave.
- **Relatório de Progresso:** Lista todos os estudos salvos e calcula automaticamente a soma de todas as horas dedicadas.
  
---

**Conceitos Praticados:**
- Estruturas de repetição (`while True`)
- Estruturas de condição (`if`, `elif`, `else`)
- Manipulação de listas paralelas (`.append()`)
- Tratamento de exceções (`try / except ValueError`)
- Formatação de strings com índices (`enumerate`)

  ---

    ### 5. Cofrinho Digital em Python ('Cofre_Digital_Python.ipynb')
Este é um projeto simples em linha de comando desenvolvido em Python para simular o controle financeiro de uma conta ou cofrinho pessoal.

---

**O que o projeto faz:**
- **Depositar Dinheiro:** Registra uma entrada financeira com a descrição da origem do dinheiro e armazena o valor positivo.
- **Retirar Dinheiro:** Registra uma saída de dinheiro (gasto), convertendo o valor digitado automaticamente para negativo no banco de dados.
- **Extrato Completo:** Lista de forma organizada todas as movimentações, diferenciando visualmente as entradas (`+ R$`) das saídas (`- R$`), além de calcular e exibir o saldo total atualizado em conta.
- **Tratamento de Exceções:** Valida as entradas do teclado para garantir que valores vazios ou letras não travem a execução do programa.

---

**Conceitos Praticados:**
- Estruturas de repetição (`while True`)
- Lógica de decisão avançada (`if`, `elif`, `else`)
- Manipulação de dados numéricos (`float` e o uso da função matemática `abs()`)
- Sincronização de listas paralelas para histórico de transações
- Tratamento de erros com bloco `try / except ValueError`

  ---

    ### 6. Simulador de Placar de Futebol ('Placar_Futebol_Python.ipynb')
Um programa simples em linha de comando desenvolvido para gerenciar e atualizar o placar de uma partida de futebol em tempo real.

**O que o projeto faz:**
- **Customização Inicial:** Permite ao usuário digitar os nomes dos dois times que vão se enfrentar antes do início do jogo.
- **Controle de Gols:** Soma e exibe na tela o placar atualizado dinamicamente toda vez que um gol é registrado para o Time 1 ou Time 2.
- **Validação de Menu:** Trata de forma inteligente as opções digitadas, exibindo um alerta de erro caso o usuário informe um número inválido, sem interromper o andamento do jogo.
- **Encerramento:** Finaliza a partida de forma limpa apenas quando a opção correta é acionada, exibindo o placar final consolidado dos times.

**Conceitos Praticados:**
- Entrada de dados dinâmica (`input()`) com strings personalizadas
- Laço de repetição contínuo (`while True`) e controle de parada (`break`)
- Estruturas de condição encadeadas (`if`, `elif`, `else`)
- Manipulação e incremento de variáveis matemáticas (`+= 1`)
- Tratamento de exceções com blocos `try / except ValueError`

    ---

    ### 7 💰 Sistema de Controle de Gastos Mensais

Este é um aplicativo utilitário em Python desenvolvido para ajudar usuários a gerenciarem suas finanças pessoais de forma simples e direta via console.

## 🚀 Funcionalidades
- **Cadastro de Despesas:** Permite inserir o nome e o valor de cada gasto.
- **Validação de Dados:** Evita a inserção de valores negativos, nulos ou campos em branco.
- **Cálculo Automático:** Exibe o total acumulado das despesas em tempo real.
- **Histórico Fluido:** Lista todos os gastos cadastrados de forma organizada.

## 🛠️ Tecnologias Utilizadas
- Python 3
- Estruturas de repetição (`while`), condicionais (`if/elif/else`) e funções (`def`).
