
# Casos de Teste — Funcionais

| ID | Cenário | Resultado esperado |
|---|---|---|
| INT-001 | Cadastro com dados válidos | Usuário cadastrado com sucesso e persistido no banco. |
| INT-002 | Envio de dados do formulário | API recebe e processa os dados corretamente. |
| INT-003 | Consulta de usuário cadastrado | Dados retornados correspondem aos dados persistidos. |
| INT-004 | Cadastro com e-mail existente | Cadastro rejeitado sem duplicação. |
| INT-005 | Validação da resposta da API | Código HTTP e corpo da resposta seguem o contrato. |

## Observação
Os cenários são propostas geradas com apoio de LLM e devem ser revisados conforme os requisitos do sistema.
