# Destack Comercial v2.6.2 — Estável

Versão de estabilização do módulo Comercial.

## O que foi corrigido
- removidos patches visuais da v2.6/v2.6.1 que estavam deformando o Dashboard e o menu;
- preservada a correção crítica do login/permissões;
- `DESTACK_ALL_PERMISSIONS` continua inicializado antes de `DEFAULT_USERS`;
- removida a identificação técnica inserida no menu lateral pelos patches anteriores;
- mantidos os módulos Comercial, Clientes, Funil, Agenda, Histórico, Ranking e Destack IA;
- estrutura Cloudflare preservada.

## Publicação
Substitua no GitHub:
- `public/index.html`
- `wrangler.jsonc`
- `README.md`

Depois aguarde o deploy da Cloudflare e teste pelo endereço online.
