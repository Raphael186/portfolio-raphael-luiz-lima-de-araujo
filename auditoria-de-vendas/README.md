# Sistema de Auditoria de Dados

## Descrição do Projeto

Este projeto consiste num algoritmo de auditoria desenvolvido para analisar e monitorizar transações comerciais. O sistema processa valores de vendas, calcula a média de desempenho e aplica regras de segurança para identificar anomalias ou discrepâncias que exijam revisão manual.

O objetivo principal é garantir o controlo financeiro e a conformidade, alertando a equipa de auditoria sempre que a média das vendas ultrapassa o limite de segurança estabelecido.

## Tecnologias e Lógica Utilizada

* **Linguagem:** Python 3.10
* **Conceitos Aplicados:** Estruturas de decisão (if/else), funções, manipulação de variáveis globais (global) e conversão de tipos de dados (casting).

## Estrutura e Funcionamento do Sistema

O algoritmo funciona em três etapas de decisão principais:

1. **Cálculo da Média e Validação:** Apresenta os tipos de dados e calcula a média das três vendas introduzidas.
2. **Verificação de Segurança:** Compara a média com o limite de segurança configurado e permite a atualização do limite em tempo real, caso necessário.
3. **Revisão Manual:** Avalia individualmente se alguma das vendas é cinco vezes superior à média, sugerindo uma auditoria rigorosa.

## Ficheiros do Projeto

* `auditoria.py`: Código-fonte principal que contém a função de análise e o fluxo de entrada de dados.

## Resultados e Aprendizados

* O sistema permite um controlo dinâmico dos limites de segurança da empresa.
* **Otimização de Auditoria:** Identificação automática de transações fora do padrão, reduzindo o esforço de verificação manual.

## Como Executar a Lógica

1. Certifique-se de que tem o Python instalado no seu computador.
2. Abra o terminal ou o seu ambiente de desenvolvimento e execute o ficheiro principal:
   ```bash
   python auditoria.py
