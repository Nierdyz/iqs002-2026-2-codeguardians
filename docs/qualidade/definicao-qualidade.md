# Definição de Qualidade

| Dimensão | Por que importa | Risco | Critério/Evidência futura |
|---|---|---|---|
| Integridade | Evitar fraudes ou alterações acidentais em avaliações | Histórico escolar adulterado | Logs de auditoria para cada inserção e modificação no banco de dados |
| Autorização | Garantir que apenas usuários com a devida permissão executem ações críticas | Aluno modificar a própria nota ou docente alterar dados de outra turma | Testes automatizados validando o controle de acesso por perfis |
| Rastreabilidade | Necessidade de auditar o fluxo e a vida útil de uma requisição | Falta de responsabilização se uma matrícula for feita acima do limite | Relatórios de logs que documentam quem realizou a ação e quando |
