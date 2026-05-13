# Processamento de Imagens e Manipulação de Matrizes em Python

## Descrição do Projeto

Este projeto foca na manipulação de estruturas de dados complexas (dicionários, listas e tuplas) para resolver três desafios práticos de lógica em Python. O código aborda desde o processamento visual de imagens pixel a pixel (alteração de cores e brilho) até a transposição matemática de matrizes aplicadas a uma biblioteca de frequências musicais.

O objetivo principal é exercitar a navegação em estruturas aninhadas e a modificação de valores em tempo de execução, utilizando a biblioteca Matplotlib para a validação visual dos resultados.

## Tecnologias e Conceitos Aplicados

* **Linguagem:** Python 3.10
* **Bibliotecas:** `matplotlib.pyplot` (para renderização visual das matrizes RGB).
* **Conceitos Aplicados:** * Navegação e atualização de Dicionários e Listas aninhadas.
  * Estruturas de repetição (`for` aninhados) para varredura de matrizes.
  * Operações matemáticas em Tuplas (divisão inteira e soma em canais RGB).
  * Lógica de transposição de matrizes (inversão de linhas e colunas).

## Estrutura das Atividades

O sistema foi dividido em três desafios principais contidos no mesmo arquivo:

1. **Desafio 1 (Filtro de Imagem - Escurecimento):** O algoritmo acessa um dicionário contendo uma grade de pixels 5x5 (representando um emoji). Ele percorre a matriz e identifica os pixels amarelos, reduzindo a intensidade da cor pela metade (divisão inteira dos canais RGB), criando um efeito de sombra/escurecimento.
2. **Desafio 2 (Transposição Musical):** O sistema acessa uma biblioteca musical que armazena "toques" como matrizes numéricas bidimensionais. O algoritmo realiza a transposição matemática dessas matrizes (transformando linhas em colunas e vice-versa) e atualiza a estrutura original.
3. **Desafio 3 (Ajuste de Brilho):** O algoritmo varre uma playlist de imagens (galeria) e altera os canais RGB de cada pixel, adicionando um valor fixo (+10) para aumentar a luminosidade. O dicionário é então atualizado com os novos valores.

## Arquivos do Projeto

* `atividade_desenvolvida.py`: Arquivo principal contendo a resolução dos três desafios de manipulação de dados e renderização visual.

## Como Executar

1. Abra o arquivo `atividade_desenvolvida.py` em um ambiente como o Google Colab ou na sua IDE local.
2. Certifique-se de ter a biblioteca Matplotlib instalada no seu ambiente (`pip install matplotlib`).
3. Execute o script. O terminal exibirá as estruturas de dados atualizadas e abrirá a visualização gráfica dos emojis processados em tela.

 ---
[Voltar ao início](https://github.com/Raphael186/portfolio-raphael-luiz-lima-de-araujo)
