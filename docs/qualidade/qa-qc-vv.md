# QA, QC, Verificação e Validação

| Prática | Classificação | Risco | Evidência | Responsável |
|---|---|---|---|---|
| Regras e permissões explícitas de acesso | QA / prevenção | Nota alterada indevidamente por usuário sem permissão | Issue com matriz de acesso aprovada | PM + TcL |
| Teste de fronteira/autorização | QC / verificação | Aluno acessar funcionalidade restrita à secretaria | Resultado do teste automatizado ou script documentado | Team Member |
| Mapeamento prévio das regras de ocupação | QA / prevenção | Matrícula acima do limite da sala | Regras documentadas na issue de desenvolvimento | PM + TcL |
| Confirmação de aderência ao processo | Validação | O sistema não refletir a regra real da instituição | Secretaria e Docentes confirmam aderência em ambiente de teste | PM + Stakeholder |
