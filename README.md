# precificacao-retorno

Página de retorno OAuth do sistema interno de precificação.
Ela apenas repassa `?code=...&state=...` do Mercado Livre para o sistema que roda no computador do usuário (`http://localhost:3210/callback/ml`).
Não guarda nem envia nenhum dado para outro lugar.
