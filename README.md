# Tabelas oficiais — Calculadora Trabalhista PRO

Fonte única das tabelas usadas pelo site. Cada usuário recebe automaticamente qualquer alteração deste arquivo, sem reinstalar nada.

- `tabelas.json` — lista de vigências (`id`, `vigencia` AAAA-MM-DD) com salário mínimo, INSS, IRRF (com o redutor da Lei 15.270/2025), salário-família e seguro-desemprego.
- O cálculo escolhe a tabela cuja `vigencia` é a mais recente anterior à data do desligamento.
- Nova tabela (ex.: janeiro/2027): adicione um novo bloco ao final da lista e atualize `versao` e `atualizadoEm`.

Atualizado por tarefa automática mensal.
