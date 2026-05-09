# Sistema de Caixa e Troco Inteligente

## Descrição do Projeto

Este projeto consiste num simulador de lógica para sistemas de PDV (Ponto de Venda), focado na estruturação do fluxo de caixa e no cálculo de troco. O objetivo principal é documentar, através de representações visuais, a automação do processo de conferência de pagamentos e a organização da entrada de produtos.

O diferencial deste desenvolvimento é a aplicação de conceitos de modularização lógica, onde o sistema é dividido em responsabilidades isoladas para facilitar a compreensão do processamento de dados. O fluxo abrange desde a soma de múltiplos itens até a validação da viabilidade financeira da transação e o retorno do saldo ao cliente.

## Documentação Visual e Tecnologias

* **Linguagem:** Lógica de Programação e Fluxogramas.
* **Conceitos Aplicados:** Estruturas Condicionais, Operadores Aritméticos e Modularização de Processos.
* **Ferramentas:** Softwares de modelagem de diagramas e leitura de algoritmos.

## Arquitetura do Sistema (Modularização Lógica)

Para garantir uma organização clara, a lógica do sistema foi estruturada em três módulos fundamentais representados nos fluxogramas:

1. **Cálculo do Total de Produtos:** Processa a entrada de diferentes produtos e suas quantidades, realizando a multiplicação e a soma sucessiva para definir o valor total a pagar.
2. **Validação de Pagamento:** Uma estrutura de decisão que verifica se o montante entregue pelo cliente é igual ou superior ao valor da compra, definindo se a transação deve ser finalizada ou se o valor é insuficiente.
3. **Cálculo de Troco:** Executa a subtração entre o valor pago e o total da compra, determinando o valor exato a ser devolvido ao cliente.

## Ficheiros do Projeto

* `fluxograma-calcular-total-de-produtos.pdf`: Detalhamento da soma de itens e quantidades.
* `fluxograma-validar-pagamento.pdf`: Lógica condicional para aprovação da compra.
* `fluxograma-calcular-troco.pdf`: Processamento matemático da devolução de valores.

## Exemplo de Fluxo Lógico

Ao processar uma venda conforme a documentação:
* O sistema lê as entradas de produtos (ex: 3 unidades a 5,00 cada) e gera o total de 15,00.
* O sistema valida se o pagamento cobre esse total.
* Caso o pagamento seja superior, o sistema calcula a diferença (Troco = Pago - Total) e exibe o resultado final.

---
[Voltar ao início](#sistema-de-caixa-e-troco-inteligente)
