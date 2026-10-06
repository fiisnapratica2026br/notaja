# NotaJá / Caderno do Pai

Frontend do controle de gastos existente. O nome final está em definição.

O bot Python e o backend permanecem em [caderno-do-pai](https://github.com/fiisnapratica2026br/caderno-do-pai), no Render. O painel integrado de teste fica em https://cadernodopai-bot.onrender.com/painel e é aberto pelo comando `/painel` no Telegram.

Este frontend é estático: não exige build nem chaves Supabase no navegador. Pode ser importado na Vercel como framework **Other**, sem comando de build, com diretório de saída na raiz.

Antes de abrir pela Vercel, configure no Render `PANEL_URL` com a URL final e `PANEL_ORIGIN` com a origem exata (por exemplo https://nome.vercel.app). A autenticação é feita via Telegram Mini App, validada no servidor. Acesso direto no navegador mostra instruções, sem dados privados.

O site não inclui o bot simulado nem o schema incompatível do ZIP anterior. Os registros, OCR e isolamento por casa vêm da aplicação existente.
