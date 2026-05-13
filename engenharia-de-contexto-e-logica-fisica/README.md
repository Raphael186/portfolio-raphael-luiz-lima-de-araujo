# Algoritmos de Análise Urbana e Navegação Espacial

## Descrição do Projeto

Este projeto consiste no desenvolvimento de dois algoritmos distintos que aplicam lógica de programação para resolver problemas de análise ambiental e segurança residencial. A primeira parte foca na monitorização de microclimas urbanos e qualidade do ar em pontos específicos, enquanto a segunda simula um protocolo de evacuação de emergência baseado em estados e tomadas de decisão.

O objetivo principal é demonstrar a aplicação de estruturas de dados (listas aninhadas), loops de repetição com validação e lógica condicional avançada em Python.

## Tecnologias e Conceitos Aplicados

* **Linguagem:** Python 3.10
* **Ambiente de Desenvolvimento:** Google Colab
* **Conceitos Aplicados:**
  * Loops `for` aninhados para processamento de métricas.
  * Estrutura `match-case` com guardas (`if`) para classificação de dados.
  * Loop `while` para simulação de estados de um agente em tempo real.
  * Lógica matemática para cálculo de métricas personalizadas (Nota de Conforto Urbano).

## Arquitetura do Sistema

O sistema está dividido em dois módulos principais contidos no mesmo ficheiro:

1. **Algoritmo do Microclima Local:** Realiza a análise técnica de locais específicos (como Praça Jauarapa, Unicid Tatuapé e Terminal Tatuapé). Processa Temperatura, Umidade e IQA para classificar a qualidade do ar e gerar uma nota de conforto de 0 a 10.
2. **Simulador de Evacuação Real:** Simula a trajetória de um agente tentando sair de uma residência até a rua. O sistema gere recursos (energia) e um inventário (chaves), aplicando penalidades ou bônus dependendo dos obstáculos enfrentados (fumaça, piso molhado, portões trancados).

## Ficheiros do Projeto

* `atividade_desenvolvida.py`: Código-fonte contendo as funções de análise de microclima e o simulador de evacuação.

## Como Executar

1. Aceda ao ambiente do Google Colab ou utilize um interpretador Python local.
2. Carregue o ficheiro `atividade_desenvolvida.py`.
3. Execute o script para visualizar no terminal o relatório completo de conforto urbano e, em seguida, o log passo a passo do simulador de evacuação.

 ---
[Voltar ao início](https://github.com/Raphael186/portfolio-raphael-luiz-lima-de-araujo)
