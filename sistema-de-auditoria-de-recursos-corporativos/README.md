# Sistema de Auditoria de Recursos Corporativos

## Descrição do Projeto

Este projeto implementa um sistema automatizado de auditoria financeira, desenhado para calcular e monitorizar o orçamento através das diferentes camadas e setores de uma estrutura corporativa complexa. O algoritmo varre uma hierarquia departamental, calcula os custos totais, permite a exclusão dinâmica de áreas específicas da auditoria e realiza conversões de moeda.

O grande diferencial deste código é a aplicação de conceitos avançados de programação funcional, incorporando um sistema de monitorização contínua que gera relatórios automáticos sobre o tempo de execução e os parâmetros processados.

## Tecnologias e Conceitos Aplicados

* **Linguagem:** Python 3.10
* **Ambiente de Desenvolvimento:** Google Colab / Ambiente Local
* **Conceitos Aplicados:**
  * **Decorators (`@auditor`):** Utilizados para estender o comportamento da função principal, registrando logs de auditoria e medindo o tempo exato de processamento (`time.perf_counter`).
  * **Recursividade:** Implementação de uma função recursiva (`recursao`) para navegar em estruturas de dados profundamente aninhadas (dicionários representando a hierarquia da empresa).
  * **Empacotamento de Parâmetros (`*args` e `**kwargs`):** Uso de argumentos variáveis para permitir a passagem flexível de departamentos a serem ignorados (`*departamentos_ignorados`) e configurações de conversão de câmbio (`**config_cambio`).

## Arquitetura do Sistema

O sistema é composto por três pilares lógicos principais contidos no mesmo arquivo:

1. **Mapeamento Estrutural:** Utiliza dicionários aninhados para simular a árvore de custos da empresa (Matriz -> TI, RH, Financeiro -> Subdepartamentos).
2. **Motor de Cálculo e Filtro:** A função `calcular_orcamento` percorre a estrutura recursivamente. Caso um departamento específico (como "Suporte" ou "Treinamento") seja passado como argumento para ser ignorado, o algoritmo descarta automaticamente esse ramo e todos os seus subníveis da soma total.
3. **Módulo de Auditoria Automática:** O decorator intercepta a execução da função de cálculo, imprime os parâmetros iniciais, monitoriza a performance em segundos e emite um relatório padronizado no terminal antes de devolver o resultado final (ajustado pela taxa de câmbio).

## Arquivos do Projeto

* `sistema_de_auditoria.py`: Código-fonte contendo a base de dados em dicionário, a lógica do decorator e a função de processamento recursivo.

## Como Executar

1. Aceda ao ambiente do Google Colab ou utilize um interpretador Python local.
2. Carregue o arquivo `sistema_de_auditoria.py`.
3. Execute o script. O terminal exibirá o relatório de auditoria gerado pelo decorator, incluindo o tempo de processamento e o valor do orçamento final formatado na moeda escolhida.

 ---
[Voltar ao início](https://github.com/Raphael186/portfolio-raphael-luiz-lima-de-araujo)
