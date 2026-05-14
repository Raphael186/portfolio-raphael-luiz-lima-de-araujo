# O Algoritmo de Auditoria de Dados

## Descrição do Projeto

Este projeto foi desenvolvido como parte de uma atividade acadêmica para exercitar a lógica de programação voltada à auditoria de sistemas financeiros e gestão de recursos. O algoritmo processa fluxos de vendas, identifica padrões de dados e aplica critérios de segurança para validar a integridade das operações corporativas.

Além do código funcional, este repositório documenta uma análise crítica sobre tratamento de dados, segurança da informação e a experiência de depuração (debugging) no ambiente Python.

## Tecnologias e Conceitos Aplicados

* **Linguagem:** Python 3.10
* **Ambiente:** Google Colab / VS Code
* **Conceitos de Auditoria:**
  * [cite_start]**Identificação de Discrepâncias:** Diferença entre valores teóricos (estoque) e reais (prateleira)[cite: 40].
  * [cite_start]**Análise de Outliers:** Identificação de dados "estranhos" ou fora do padrão em um sistema[cite: 41].
  * [cite_start]**Normalização de Dados:** Padronização de informações para evitar erros de processamento e resultados inesperados[cite: 42].
  * [cite_start]**Margem de Tolerância:** Gestão de limites operacionais ou "teto de gastos" pelo auditor[cite: 43].

## Análise de Compreensão e Metacognição

Como parte do desenvolvimento, foram realizados testes de estresse e reflexões sobre a arquitetura do software:

### 1. Teste de Estresse (Análise de Mesa)
[cite_start]Durante os testes com os valores (Venda 1: 100, Venda 2: 200, Venda 3: 5000), a média resultante foi de **1.766,66**[cite: 45]. [cite_start]Embora o valor 5000 fosse consideravelmente alto, o código processou a informação conforme a lógica programada, demonstrando a importância de configurar alertas específicos para valores discrepantes[cite: 45].

### 2. Segurança e Aplicação Real
[cite_start]Foi identificada uma vulnerabilidade crítica no uso de **variáveis globais** para limites de segurança em contextos bancários[cite: 46]. [cite_start]Em um cenário real, o uso de variáveis não protegidas permitiria que usuários sem autorização (como outros funcionários além do gerente) alterassem limites de segurança sem que o sistema detectasse a infração[cite: 46].

### 3. Experiência de Desenvolvimento (Debugging)
O processo de elaboração enfrentou desafios técnicos comuns em Python, como:
* [cite_start]**NameError:** Erro na variável `LIMITE_SEGURANCA` devido à presença de espaços e uso de maiúsculas, o que fez o interpretador ler apenas o termo "LIMITE"[cite: 47].
* [cite_start]**Indentação:** Erros de espaçamento nas variáveis de venda e na definição da função `analisar_vendas`[cite: 48].
* [cite_start]**Solução:** A otimização foi realizada através da análise das mensagens de erro do Python e suporte de ferramentas de IA integradas para refinamento do código[cite: 48].

## Estrutura do Repositório

* `sistema_de_auditoria.py`: Código-fonte principal com a lógica de cálculo e validação.
* `Análise_Metacognição.pdf`: Documento detalhado com as respostas teóricas e testes de mesa realizados[cite: 39].

## Como Executar

1. Clone este repositório.
2. Certifique-se de ter o Python instalado.
3. Execute o script principal para visualizar o processamento das vendas e o relatório de auditoria.

---
[Voltar ao início](#o-algoritmo-de-auditoria-de-dados)
