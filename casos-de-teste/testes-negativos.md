
# Casos de Teste — Negativos

| ID | Cenário | Resultado esperado |
|---|---|---|
| INT-006 | Cadastro sem nome | Solicitação rejeitada conforme as regras de validação. |
| INT-007 | E-mail inválido | Erro de validação e ausência de cadastro. |
| INT-008 | E-mail duplicado | Cadastro rejeitado sem duplicar o registro. |
| INT-009 | Banco indisponível | Falha tratada sem retorno indevido de sucesso. |
| INT-010 | Timeout na comunicação | Erro tratado conforme a política definida. |
| INT-011 | Falha na gravação | Dados mantidos consistentes, sem registros indevidos. |

## Observação
Os resultados esperados devem ser confirmados com o contrato da API e os requisitos do sistema.
