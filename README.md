# Desafio RPA Developer UiPath - Redesign

## Descrição do Desafio
Este repositório contém a solução para o Desafio RPA Developer UiPath da empresa Redesign. O objetivo é construir duas automações distintas que realizam o mesmo processo: o cadastro de oportunidades para o time de Vendas.

## Objetivo
### Automação 1 - Importar Dados:
- Extrair todas as informações da tabela do site Report: Opportunities[https://www.rpasamples.com/opportunities].
- Enviar os dados extraídos para uma fila no UiPath Orchestrator.

### Automação 2 - Exportar e Preencher Forms:
- Pegar as informações da fila no UiPath Orchestrator.
- Cadastrar os itens no sistema Forms, filtrando apenas os de origem USA e Germany.
- Enviar um e-mail indicando a conclusão do processo.
