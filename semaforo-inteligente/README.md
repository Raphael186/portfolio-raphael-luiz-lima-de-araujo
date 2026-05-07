Sistema de Semáforo Inteligente
Descriçao do Projeto
Este projeto consiste na lógica de um motor de controlo inteligente para semáforos, desenvolvido para otimizar o
f
luxo de tráfego urbano em tempo real. O sistema utiliza estruturas de decisão para equilibrar o tempo de sinal
verde e vermelho com base na quantidade de veículos e pedestres detetados nas vias. 
O objetivo principal é mitigar congestionamentos e garantir a segurança dos pedestres, ajustando dinamicamente
os tempos de semáforo de acordo com o fluxo medido. 
Tecnologias e Lógica Utilizada
• 
• 
• 
Linguagem / Lógica: Pseudocódigo estruturado e Fluxograma
Ferramentas de Documentação: Editor de fluxogramas e leitura de algoritmos
Conceitos Aplicados: Estruturas de condição (se/senão), contadores e operadores relacionais
Estrutura e Funcionamento do Sistema
O algoritmo funciona em três etapas de decisão principais: 
1. 
2. 
3. 
Prioridade de Veículos: Adiciona tempo ao sinal caso a quantidade de veículos seja igual ou superior a 10.
Prioridade de Pedestres: Ajusta o tempo de travessia caso o número de pedestres esteja dentro da faixa de
segurança (entre 5 e mais pessoas).
Balanceamento de Fluxo: Compara o número de veículos e pedestres para priorizar a via com maior procura.
Ficheiros do Projeto
PSEUDOCODIGO00.pdf
PSEUDOCODIGO01.pdf
FLUXOGRAMA-SEMAFORO.pdf 
Resultados e Aprendizados
• 
• 
O algoritmo atinge um tempo de base de 30 segundos para ambas as vias, aumentando o tempo
dinamicamente conforme a procura.
Otimização de Fluxo: Implementação de regras para priorizar pedestres ou veículos conforme o volume de
tráfego.
Como Executar a Lógica
1. 
2. 
3. 
Abra o ficheiro FLUXOGRAMA-SEMAFORO.pdf para entender o fluxo de leitura das entradas.
Leia o ficheiro PSEUDOCODIGO00.pdf para configurar as variáveis iniciais.
Confira os resultados lógicos no ficheiro PSEUDOCODIGO01.pdf.
Desenvolvido com boas práticas de versionamento e documentação | Voltar ao início
