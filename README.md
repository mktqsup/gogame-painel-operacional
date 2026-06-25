# GO GAME 2026 - Painel Operacional

Painel estatico para acompanhamento de entregas, agenda, aprovacoes e desempenho do Instagram.

## Hospedagem

Este pacote pode ser publicado diretamente no GitHub Pages, Netlify ou Vercel.

Arquivos principais:

- `index.html` - aplicacao do painel
- `supabase-config.js` - configuracao publica do Supabase
- `assets/` - logos, fontes e arquivos aprovados usados pelo painel

## Supabase

A visualizacao e publica. A edicao exige login por magic link no Supabase Auth.

Depois de publicar, adicione a URL final em:

Authentication -> URL Configuration -> Redirect URLs

Tambem defina a mesma URL em Site URL se esse painel for o destino principal de login.
