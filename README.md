# Testes de Integração com LLM

## Objetivo

Explorar o uso de uma LLM para apoiar a criação de casos de teste de integração em um sistema de cadastro de usuários, composto por front-end, API REST e banco de dados.

## Prompts utilizados

**Prompt 1 — Cenários funcionais**

Utilizado para gerar testes de integração relacionados ao fluxo de cadastro, processamento das informações, persistência dos dados e respostas da API.

**Prompt 2 — Cenários negativos**

Utilizado para identificar falhas relacionadas a dados inválidos, cadastros duplicados, indisponibilidade do banco e problemas de comunicação.

## Resultados

Foram elaborados 11 casos de teste, contemplando cenários funcionais e negativos.

O primeiro prompt favoreceu a organização dos cenários principais do sistema. O segundo ampliou a cobertura ao considerar situações de falha e consistência dos dados.

## Análise

Foi necessário detalhar o contexto do sistema, os componentes envolvidos e os campos esperados em cada caso de teste.

Também foi importante solicitar resultados estruturados e orientar a LLM a não presumir regras de negócio não especificadas.

## Conclusão

A utilização de prompts bem definidos pode apoiar a criação e diversificação dos testes de integração. Entretanto, os casos gerados precisam ser revisados pelo QA e comparados com os requisitos e contratos da API antes da execução.
